---
title: "Tip and tricks Laravel"
author: "Vincent Tarrit"
date: 2022-12-12
draft: false
summary: "Quelques tips and tricks pour Laravel"
blog_tags: ["laravel", "développement"]
---

# Quelques tips and tricks pour Laravel

Cet article décrit différents trucs et astuces pour utiliser efficacement l'ORM de Laravel nommé "Eloquent". Cet article à pour but de graver les bonnes idées afin de réduire et améliorer la lisibilité et l'efficacité d'un site internet développé en Laravel.

# 1

A la place de:

```php
$article = Article::find($article_id);
$article->read_count++;
$article->save();
```

Vous pouvez écrire:

```php
$article = Article::find($article_id);
$article->increment('read_count');
```

Ou alors en une ligne:

```php
Article::find($article_id)->increment('read_count');
Article::find($article_id)->increment('read_count', 10); // +10
Product::find($produce_id)->decrement('stock'); // -1
```

# 2

A la place de:

```php
$user = User::find($id);
if (!$user) { abort (404); }
```

Vous pouvez écrire:

```php
$user = User::findOrFail($id);
```

# 3

Vous pouvez utiliser la fonction boot qui permet d'effectuer des actions avant ou après la création/sauvegarde/modification du model.

```php
public static function boot()
{
  parent::boot();
  self::creating(function ($model) {
    $model->uuid = (string)Uuid::generate();
  });
}

```

# Sources

- https://laravel-news.com/eloquent-tips-tricks (24 janvier 2023 à 10:26)
