---
title: "Mon expérimentation de veille"
author: "Vincent Tarrit"
date: 2022-12-12
draft: false
summary: "Qu'ai-je fait avec un outil de veille?"
blog_tags: ["développement"]
---

En naviguant sur Twitter, j'ai découvert l'outil Filament, un puissant framework full-stack à l'intérieur de Laravel. Il utilise le stack TALL: [TailwindCSS](https://tailwindcss.com/), [AlpineJS](https://alpinejs.dev/), [Laravel](https://laravel.com) et [Livewire](https://laravel-livewire.com/).

Pour pouvoir l'expérimenter de manière efficace j'ai décidé de l'utiliser dans un projet réel. En effet un ami avait besoin d'un logiciel de gestion de membre pour son club de [judo](https://dojopalettes.ch)

L'idée de cet outil est de proposer une gestion CRUD vraiment simplifier. En effet, pour générer une gestion complète sur un [model](https://laravel.com/docs/9.x/eloquent) il suffit de lancer cette ligne :

```bash
    php artisan make:filament-resource UserResource --generate
```

Cette ligne va créer une table de liste avec tous les modèles, une page d'édition et une page de création.

Pour faire simple, il met à disposition un outil performant pour démarrer rapidement une administration pour Laravel.
