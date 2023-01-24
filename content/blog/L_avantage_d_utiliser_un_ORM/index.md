---
title: "L'avantage d'utiliser un ORM"
author: "Vincent Tarrit"
date: 2022-12-12
draft: false
summary: "Quel est l'avantage d'utiliser un ORM ?"
blog_tags: ["développement"]
---

# Pourquoi ai-je choisi cet article ?

L'utilisation d'un ORM devient de plus en plus naturel dans tous les framework web. Je trouve intéressant de se poser la question du pourquoi utiliser un tel ou tel outil plutôt que de l'utiliser les yeux fermés.

# Quel est l'avantage d'utiliser un ORM ?

L'utilisation d'un ORM (Object Relational Mapping) pour manipuler des données dans la construction d'une application apporte des avantages tels que la réduction du code à écrire et à maintenir, l'homogénéité du code objet et l'accélération du temps de développement. Cependant, ces avantages sont souvent contrebalancés par des inconvénients tels que les limites dans la manipulation de modèles de bases de données plus complexes et la dépendance à des bibliothèques supplémentaires. La décision d'utiliser un ORM dépend donc des avantages de ces dépendances supplémentaires en fonction de l'effort nécessaire pour le projet. Il est préférable d'utiliser un ORM de manière modérée et circonstanciée pour tirer le meilleur parti de ses avantages et éviter ses inconvénients.

<img src="/images/orm.png">

## Les avantages d'un ORM (Object Relational Mapping) comprennent :

- La réduction de la quantité de code à écrire et à maintenir pour manipuler des données dans la base de données depuis l'application.
- L'homogénéité du code objet, car il permet de travailler avec des objets plutôt que des lignes de code SQL.
- L'accélération du temps de développement, car il simplifie les tâches de manipulation de données.
- La possibilité de changer de système de gestion de base de données sans avoir à modifier le code de l'application.

## Les inconvénients d'un ORM incluent :

- Les limites dans la manipulation de modèles de bases de données plus complexes.
- Une dépendance à des bibliothèques supplémentaires, ce qui peut rendre le projet plus complexe à gérer.
- Une performance moins bonne par rapport à l'utilisation directe du SQL.
- Les ORM ne sont pas toujours adaptés à tous les besoins, il faut donc être conscient de cela pour pouvoir choisir le bon ORM pour votre projet.

# Sources

- https://sgbd.developpez.com/actu/261037/Faut-il-utiliser-les-ORM-ou-continuer-d-ecrire-simplement-des-requetes-SQL-Eli-Bendersky-donne-son-avis/ (24 janvier 2023 9:47)
