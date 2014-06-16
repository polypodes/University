# Formation Javascript

## Les compétences que valide cette formation

- Mettre en place un outillage pour assurer qualité du code 
- Maîtriser les tests unitaires et les tests de comportement en PHP
- Utiliser un système de gestion de dépendances (package Manager) : Composer
- Mettre en oeuvre un serveur d'intégration continue: Jenkins, Travis ou Sismo
- Organiser, documenter et tester son code
- Organiser la recette et le debug d'une application PHP avec un outil de _ticketing_: Redmine, Github ou Bitbucket
- Mise en application : Suite de workshops autour d'une API REST avec PHP

## Durée

- 3 jours

## Public

- développeurs PHP junior

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

### a PHP upgrade
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

#### Workshop: Installer et utiliser SwitMailer, envoyer des emails avec l'API d'un SMTP tiers

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

### Serious PHP

- KISS
- DRY
- SOLID PHP
- _PHP jokes_: typage et méthodes magiques

### Aperçu des Design Patterns et éléments d'architecture des projets PHP


- Utiliser le 
- Utiliser le pattern MVC
- Utiliser un ORM ? (Doctrine)
- Utiliser le pattern Front Controller via un micro-framework PHP (Silex)
- Utiliser le Conteneur d'Injection de Dépendances (Pimple via Silex)
- Utiliser un framework de tests (PhpUnit)
- Utiliser un serveur d'intégration continue (SISMO, Travis-CI ou Jenkins)
