---
title: "L'avantage d'utiliser un ORM"
author: "Vincent Tarrit"
date: 2022-12-12
draft: false
summary: "Quel est l'avantage d'utiliser un ORM ?"
blog_tags: ["développement"]
---

# Quel est l'avantage d'utiliser un ORM ?

## Introduction

Les ORM (Object-Relational Mapping) sont des outils qui permettent aux développeurs de travailler avec des bases de données relationnelles de manière plus orientée objet. Cela signifie que les données stockées dans la base de données sont représentées par des objets dans le code de l'application, plutôt que de travailler directement avec des requêtes SQL. Les ORM sont conçus pour faciliter la communication des développeurs avec les bases de données et le code d'application.

## Avantages

### Productivité

Un ORM peut aider les développeurs à se concentrer sur la logique de leur application, plutôt que de se soucier des détails de la façon dont les données sont stockées et extraites d'une base de données.

### Portabilité

Un ORM est un outil qui vous aide à gérer les données de votre application en prenant en charge les modifications apportées à la structure de la base de données. Cela signifie que vous pouvez vous concentrer sur le développement de votre application au lieu d'avoir à vous soucier des détails de la base de données.

### Sécurité

Les ORM vous aident à vous protéger contre les attaques par injection SQL en échappant automatiquement les caractères spéciaux dans votre entrée avant de les utiliser dans les requêtes SQL.

### Pour les développeurs

Un ORM est un outil qui permet aux développeurs de créer automatiquement des requêtes SQL, ce qui peut rendre le travail avec la base de données plus efficace. Cela signifie que les développeurs n'ont pas à écrire constamment eux-mêmes des requêtes SQL personnalisées.

## Inconvénients

### Performance

Les ORM peuvent rendre les requêtes SQL plus rapides que si vous les écriviez vous-même, surtout si la requête est compliquée ou implique une grande base de données. Les ORM traduisent les requêtes de l'application en code SQL avant de les exécuter, afin que le code soit exécuté plus rapidement.

### Difficulté de travail

Un inconvénient des ORM est qu'ils peuvent être plus difficiles à comprendre et à déboguer que les requêtes SQL écrites manuellement. Les développeurs doivent se familiariser avec le fonctionnement de l'ORM et la façon dont il traduit les requêtes d'application en requêtes SQL, ce qui peut prendre du temps si vous n'êtes pas familiarisé avec l'une ou l'autre de ces choses.

Un "ORM" est un outil qui vous aide à travailler avec des bases de données plus facilement que si vous travailliez directement avec des requêtes SQL. Lorsque des erreurs se produisent, il peut être plus difficile de les diagnostiquer et de les corriger dans les requêtes SQL, mais avec un ORM, il peut être plus facile de voir où se situe le problème.

## Quels sont les ORM les plus utilisés ?

### Hibernate (Java)
[https://hibernate.org/](https://hibernate.org/)

### Eloquent (Laravel/PHP)
[https://laravel.com/docs/9.x/eloquent](https://laravel.com/docs/9.x/eloquent)

### Ruby on Rails ActiveRecord (Ruby)
[https://guides.rubyonrails.org/active_record_basics.html](https://guides.rubyonrails.org/active_record_basics.html)

### Django ORM (Python)
[https://docs.djangoproject.com/fr/4.1/topics/db/queries/](https://docs.djangoproject.com/fr/4.1/topics/db/queries/)

### EF Core (C#)
[https://learn.microsoft.com/en-us/ef/core/](https://learn.microsoft.com/en-us/ef/core/)

## Conclusion

Les ORM sont des outils qui permettent aux développeurs back-end de travailler avec des bases de données relationnelles à l'aide d'une interface orientée objet. Ils présentent des avantages tels que la possibilité d'abstraire la base de données, d'être portables et d'avoir des fonctionnalités de sécurité, mais ils peuvent également avoir des inconvénients, comme des performances plus lentes et une complexité accrue. Il existe de nombreux ORM différents, chacun avec ses propres caractéristiques et fonctionnalités. Les développeurs doivent évaluer les besoins de leur application pour déterminer si un ORM est approprié pour leur projet.

## Sources

- https://www.editions-eni.fr/open/mediabook.aspx
- https://fr.wikipedia.org/wiki/Mapping_objet-relationnel
- https://www.base-de-donnees.com/orm/
