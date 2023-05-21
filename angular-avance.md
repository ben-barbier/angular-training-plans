# Titre

Angular Avancé

# Description

**Angular** est un framework de développement d'applications web porté par Google. Sans doute le plus polyvalent et le plus complet des frameworks actuels, il offre une expérience de développement sans comparaison.

Durant cette formation Angular Avancé, nous plongerons dans les concepts avancés (zones, lazy loading, i18n strategies, ...) d'**Angular** et découvrirons son écosystème (RxJS, @ngrx, material, PWA, ...). Cette formation porte sur la **dernière version** majeure du framework de Google (Angular 16).

La **formation Angular Avancé** est destinée à des **développeur·se·s ayant déjà pratiqué le framework sur un projet** et souhaitant comprendre le rôle des mécanismes internes du framework. L'objectif est également de structurer le tout à travers un ensemble de **bonnes pratiques**, de **retours d'expérience** et de tips afin de rendre les applications réalisées maintenables et évolutives.

Cette formation, orientée **pratique**, permettra à chacun des participant·e·s de produire une application Angular sur la base d'une API REST existante. L'application réalisée étant opérationnelle, elle pourra servir de modèle pour leurs projets à venir.

Si vous débutez avec le framework Angular, jetez un œil à notre [formation Angular](https://www.humancoders.com/formations/angular) !

Enfin pour **approfondir les fonctionnalités offertes par la librairie RxJS**, jetez un œil à notre [formation RxJS](https://www.humancoders.com/formations/rxjs). Cette dernière couvre toutes les fonctions et opérateurs RxJS qui permettent de créer, combiner et transformer des Observables.


# Objectifs pédagogiques

* Comprendre les concepts avancés qui portent Angular
* Augmenter les performances d'une application Angular
* Intégrer les librairies externes incontournables

# Travaux pratiques à évaluer

- Initialiser et configurer un projet Angular scalable avec angular material, prettier, eslint, jest, esbuild et vite
- Faire évoluer l'application en y intégrant plusieurs pages, un template complet et l'internationalisation.
- En utilisant les concepts et opérateurs RxJS présentés, créer un panier et intégrer celui-ci dans plusieurs pages de l'application.
- Grace aux signaux, optimiser et simplifier les mécanismes de rendering de l'application développée.
- Implémenter un state management avec NGRX

# Pré-requis

* Avoir eu un premier contact avec une application angular. Cela implique une bonne connaissance de TypeScript (et de JavaScript) et une connaissance suffisante des concepts de base utilisés dans Angular : Components, Services, Forms, Routing, Observables, ...

# Programme

**Note :** un rappel / mise à niveau sur Angular est effectué au début de la formation : Component, Forms, Routing, Services, Observables, ...

#### 1. Concepts avancés

##### JavaScript / Typescript

* Tips & tricks
* Pure functions
* Arrays & Functional programming

##### Functional Reactive Programming & **RxJS**

* Concepte
* Principaux opérateurs
* Opérateurs de combinaison
* Gestion des exceptions
* De l'API à la vue avec le pipe Async

##### Zone & Change detection strategies

* Principe et utilité
* État de la vue (component)
* Propagation du changement

##### PWA

* Théorie et contexte
* Cache
  * Static Content Cache
  * Dynamic Content Cache
* Service Workers
* Push Notifications

##### Lazy Loading & Module architecture

* Améliorer les performances de démarrage
* Route integration : loadChildren
* Preloading
* Modules partagés

***Mise en pratique***
- _Initialiser et configurer un projet Angular scalable avec [angular material](https://material.angular.io/), [prettier](https://prettier.io/), [eslint](https://eslint.org/), [jest](https://jestjs.io/fr/), [esbuild](https://esbuild.github.io/) et [vite](https://vitejs.dev/)_
- _Faire évoluer l'application en y intégrant plusieurs pages, un template complet et l'internationalisation_

##### Injection de dépendances

* Principes de l'injection de dépendance
* Injection hiérarchique
* Inject anything : InjectionToken

##### Route guards & resolve

* Les différents types de Guards
* CanActivate, CanActivateChild : protéger une route
* CanDeactivate : sécuriser la sortie
* Pre-fetching avec resolve

***Mise en pratique***
- _En utilisant les concepts et opérateurs [RxJS](https://rxjs.dev/) présentés, créer un panier et intégrer celui-ci dans plusieurs pages de l'application_
- _Grace aux signaux, optimiser et simplifier les mécanismes de rendering de l'application développée_

#### 2. Écosystème

##### Angular Material

* Configuration et theming
* Étude et mise en oeuvre de quelques composants
* Material & CDK

##### Le "State Management Pattern" avec NgRx

* Concept : Immutable data store
* Store : Reducers & Actions par la pratique
* Effects : Gestion des actions asynchrones
* Entity : Performance et volumétrie

##### Angular Universal

* Introduction

##### Internationalisation (aka I18N)

* Angular I18N standard
  * i18n marker
  * Singulier / pluriel & select
  * ng-xi18n
  * AOT gotchas
* @ngx-translate
  * Concept de la librairie
  * Chargement à chaud des traductions

***Mise en pratique***
- _Implémenter un state management avec [NGRX](https://ngrx.io/)_

# Supports pédagogiques

- https://angular.io/docs
