# RdvMedecins - Un exemple de client / serveur avec NestJS et Angular

**Le cours est en ligne ici : [https://stahe.github.io/angular-nestjs-sept-2026/](https://stahe.github.io/angular-nestjs-sept-2026/)**

Ce dépôt ne contient que ce README : le cours lui-même est publié à l'adresse ci-dessus.

## Présentation

Ce cours construit, étape par étape, une application complète de prise de rendez-vous médicaux (« RdvMedecins ») : un serveur web NestJS/TypeScript exposant une API JSON, une base de données MySQL, et un client Angular consommant cette API. Il se termine par une authentification par jetons JWT avec contrôle d'accès par rôles (ADMIN/USER).

C'est un portage vers des technologies actuelles du cours [*Un exemple de client / serveur - AngularJS 1.x / Spring 4*](https://stahe.github.io/spring-angular1.x-juillet-2014/) (2014) : même étude de cas, même architecture en couches, mais un serveur Java/Spring remplacé par NestJS/TypeScript et un client AngularJS 1.x remplacé par Angular (composants standalone, signaux).

## Ce que vous trouverez dans le cours

- La mise en place de l'environnement de travail (Node.js, MySQL, Visual Studio Code) et la création de la base de données ;
- Une introduction à NestJS : modèle de développement, décorateurs, injection de dépendances, à travers un mini-projet avant l'étude de cas ;
- La construction complète du serveur NestJS de RdvMedecins : entités TypeORM, couche DAO, couche métier, couche web (contrôleurs et routes JSON) ;
- Une introduction à Angular : d'AngularJS 1.x à Angular actuel, composants, signaux, composants standalone, injection de dépendances, communication HTTP, nouvelle syntaxe de contrôle de flux (`@if`, `@for`) ;
- La construction complète du client Angular de RdvMedecins : modèles, services, intercepteurs, traduction français/anglais de l'interface, composants ;
- L'ajout d'une authentification par jetons JWT et d'un contrôle d'accès par rôles (ADMIN/USER) ;
- Une conclusion récapitulant ce qui a été construit et les pistes pour aller plus loin.

Chaque explication de code reprend les identifiants exacts du code montré (tables, colonnes, classes, décorateurs...), afin de rester précise et de bien suivre le fil des exemples.

## Prérequis

Le document ne suppose pas de connaissance préalable de NestJS ni d'Angular. Une familiarité avec TypeScript et les bases du développement web (HTTP, JSON, bases de données relationnelles) facilite la lecture.

## Auteur

**IA Claude d'Anthropic** et révisé par Serge Tahé - Septembre 2026
