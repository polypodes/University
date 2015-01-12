# Formation PHP Avancé : Qualité et industrialisation

## Les compétences que valide cette formation

- Mettre en place une politique de qualité du code en équipe
- Mettre en place un outillage pour assurer et mesurer la qualité du code 
- Utiliser un système de gestion de dépendances (package Manager) : Composer
- Maîtriser les tests unitaires et les tests de comportement en PHP
- Connaître les Design Patterns et éléments d'architecture des projets PHP
- Connaitre les principes KISS, DRY, SOLID, et les mettre en oeuvre
- Utiliser un système de build et un serveur d'intégration continue et outil de _ticketing_
- Mise en application : Suite de workshops autour d'une API REST avec PHP

Inspiration: - [phptherightway.com](http://www.phptherightway.com/), [phpbestpractices.org](http://phpbestpractices.org), [phpqatools.org](http://phpqatools.org/), [Jenkins-PHP.org](jenkins-php.org)l'expertise et l'expérience du formateur

## Durée

- 3 jours

## Public

- développeurs PHP juniors et motivés !

## Prérequis

- Notions de développement de page web avec HTML
- Notions de développement côté serveur avec PHP

## Methode pratique

Courte présentation de chaque point, réponses aux questions, et travaux dirigés en groupe, sous la forme de workshops, un par chapitre de la formation.

## Programme détaillé de la formation

## Premier jour

### PHP orienté qualité

- Qu'appelle-t-on exactement la "qualité"
- Définit un périmètre d'assurance qualité
- Partager l'information sur la qualité du code

#### Workshop: Etablir une checklist qualité

### _a PHP upgrade_
- Actualité du langage PHP et de son écosystème
- Nouveautés de PHP 5.4.x / 5.5.x / 5.6.x
- PHP-FIG (Framework Interoperability Group) et les PSR (Proposed Standards Recommendations)
- Outils essentiels pour coder en PHP 5.x stable dans Vim+bundles, Eclipse+PHP Development Tools, Sublime ou PhpStorm

#### Workshop: Choisir et configurer un éditeur de code RAD: Vim+bundles, Eclipse+PHP Development Tools, SublimeText ou PhpStorm

### Savoir configurer PHP

- Utiliser plusieurs version de PHP (Mac / Windows / Linux)
- Configurer PHP selon que l'on soit en environmment de développement ou de production
- Comprendre les options de php.ini
- Utiliser Xdebug
- Configurer son IDE pour le debug pas-pas

#### Workshop: Debug PHP pas à pas avec Eclipse, SublimeText ou PhpStorm

### Composer et la gestion des dépendances

- Définir un projet PHP avec composer.json
- Définir et obtenir les dépendances (bibliothèques PHP tierces)
- Trouver évaluer et intégrer des projets PHP Open-Source utiles dans un projet en cours 

#### Workshop: Installer et utiliser SwiftMailer ou Mandrill (API PHP, SMTP tierce)

## Deuxième jour

### Aperçu des Design Patterns et éléments d'architecture des projets PHP

- Utiliser le pattern MVC
- Utiliser un ORM ? (Doctrine2) ou un OMM (POMM) ? ou rien du tout ?
- Utiliser le pattern Front Controller via un micro-framework PHP (Silex)
- Utiliser le Conteneur d'Injection de Dépendances (Pimple via Silex)

### Les tests unitaires, les tests fonctionnels, les tests de comportements

- Où commencent et s'arrêtent les tests : quoi et pourquoi tester du code ?
- Construire une assurance anti-régression en capitalisant sur les tests
- PHPUnit et les objectifs réels et utiles de _couverture de code_
- WebTestCase (Symfony2 ou Silex) : les tests fonctionnelles appliqués au web
- Behat et la _business value_ réelle d'un développement PHP

#### Workshop: "Green code": Pratiquer le TDD et le BDD sur une petite API REST PHP

### Building: Automatiser les tâches

- Présentation de Phing
- Présentation de Capistrano / Capiphony
- Ce bon vieux Makefile

#### Workshop: "Green build": Utiliser un système de build

### Continuous Integration: Communiquer autour de la qualité d'un développement PHP

- Présentation de Jenkins
- Présentation de Travis-ci
- Présentation Scrutinizer-ci
- Présentation de SISMO

#### Workshop: "Green integration": Utiliser un serveur d'intégration continue

## Troisième jour

### Feedback & support: Automatiser les tâches de maintenance

- Gestion des demandes via les issues de Github
- Gestion des demandes via les issues de Bitbucket
- Gestion des demandes via Redmine

#### Workshop: Partger l'API Workshop sur Github et définir/qualifier/affecter un jalon, _fixer_ via git commit

### PHP Quality Toolchain pour auditer du code PHP

- Mesurer, avant de ré-écrire ou de prendre en charge une TMA
- Les premiers les indices de qualités : documentation, versioning, style, dépendances et couplages, error handling, paramétrages
- _php-linting_ en pratique dans un IDE ou en ligne de commande
- La _quality toolchain_ de PHP : phpcs, php-loc, phpmd, phpdcd, phpcpd

#### Workshop: Obtenir des métriques qualité sur un projet PHP ancien, avant d'initier un refactoring

### PHP With style

- Pourquoi choisir un Coding Style Standard ?
- Vérifier le respect un Coding Style Standard
- Corriger continuellement les erreurs de styles avec php-cs-fixer
- Au-delà du seul Coding Style Standard, défendre la lisibilité du code

#### Workshop: Mettre en oeuvre php-cs-fixer sur un projet PHP existant

### Documenter

- Le README.md, ou comment se mettre à la places des autres
- Comprendre et utiliser la syntaxe PHPDoc
- Faut-il commenter son code au-delà de phpdoc
- Générer une documentation avec PHPDoc

### Serious PHP

- KISS
- DRY
- SOLID PHP
- _PHP jokes_: typage et méthodes magiques

#### Workshop: Mettre en oeuvre une API REST en garder en tête ces principes, démontrer qu'ils sont respectés

### _Future PHP_

Une petite présentation de HHVM et un exemple d'utilisation avec `composer`
