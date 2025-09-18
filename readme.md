# Bienvenue sur mon portfolio

## OpenClassroom

Présentation de mes solutions aux différents projets réalisés lors de ma formation "développeur d'application python" chez OpenClassroom

### Projet : [Analyse de marché](https://github.com/spleenYou/OC-P2)

Le projet met en place la récupération d'informations sur des livres chez un revendeur.\
La sauvegarde des informations se fait au format CSV.\
Les premières de couvertures sont également sauvegardées.\
Le tout trié par catégorie.

Apprentissage :
- Base du python
- Mise en place d'un pipeline ETL
- Contrôle de version sur Github

### Projet : [Tournoi d'échec](https://github.com/spleenYou/OC-P4)

Ce projet est la conception d'un logiciel de tournoi d'échec avec sauvegarde des informations en local.

Apprentissage :
- Programmation orientée objet
- Design pattern MVC
- Sauvegarde des informations au format JSON
- Standard PEP8

### Projet : [Interface utilisateur pour une application web](https://github.com/spleenYou/OC-P6)

Le projet est la création d'une interface web responsive pour une association cinéphile affichant les meilleurs films dans diverses catégories.\
La dernière section a un menu permettant la selection de la catégorie a afficher.

Apprentissage :
- HTML
- CSS
- Base du javascript
- Utilisation d'une API REST

### Projet : [Les algorithmes](https://github.com/spleenYou/OC-P7)

Le projet consiste en la recherche d'une solution d'achat d'actions selon une liste fournie au format CSV.\
Le but est de trouver la liste la plus rentable pour un montant d'achat donné.\
La première solution se fait en burte-force, la deuxième est basé sur une résolution du problème du sac à dos pour une optimisation du temps d'exection.

Apprentissage :
- Notion big-O
- Limite de résolution d'un algorithme
- Utilisation du package Rich
- Mesure de temps d'éxecution du programme

### Projet : [Application web Django](https://github.com/spleenYou/OC-P9)

Le projet consiste en la construction d'un MVP d'un site en local.\
L'application permet à une communauté d'utilisateurs de publier des critiques de livres ou d’articles et de consulter ou de solliciter une critique de livres à la demande.

Les fonctionnalités principales :
- Billets
    - Demandes de critiques pour des livres ou articles
    - Possibilité de créer un billet et une critique simultanément
- Flux personnalisé
    - Affiche billets et avis des utilisateurs suivis et de l'utilisateur connecté
    - Inclut les réponses aux billets de l'utilisateur connecté
    - Trié par ordre antéchronologique
- Système de suivi
    - Suivi d'autres utilisateurs pour voir leurs critiques
    - Interface simple pour la gestion des suivis
- Authentification
    - Inscription et connexion requises pour accéder aux fonctionnalités

Apprentissage :
- Django
- WCAG

### Projet : [API sécurisé](https://github.com/spleenYou/OC-P10)

Le projet consiste a créer une API RESTful en utilisant Django REST avec une identification OAUTH2.\
L'API permet de remonter et suivre des problèmes techniques avec gestion de groupes de contributeurs par projet et par problème.
Elle utilise une authentification via JWT et respecte le RGPD car chaque contributeur peut choisir s'il peut être contacter et si leurs données personnelles peuvent être vu par tous.
L'API tend vers des spécifications green code en envoyant le plus d'informations utiles possible en une fois afin d'éviter la surconsommation des serveurs.

Apprentissage :
- Django REST
- Postman

### Projet : [Amélioration d'une application Web Python](https://github.com/spleenYou/OC-P11)

Le projet consiste à reprendre un site web pour corriger ses bugs avec une utilisation plus professionnelle des branches Github.
Avec vérification de ses performances en cas d'utilisation intensive.
Mise en place de vérification et limite suivant un cahier des charges.

Apprentissage :
- Flask
- Locust

### Projet : [Architecture back-end sécurisée](https://github.com/spleenYou/OC-P12)

Le projet consiste à developper un CRM interne de gestion de clients et d'évènements.
L'objectif est de mettre en place une base de données sécurisée et fiable.
Les mots de passe sont sauvegarder après hashage via Argon2.
L'accès aux actions et informations sont définies par des rôles utilisateurs et un JWT.
En cas d'erreur dans le code, elle est remonté sur Sentry pour une analyse rapide.

Apprentissage :
- MySQL
- SQLalchemy
- Sentry

### Projet : [Mettre en place une app Django en utilisant une architecture modulaire](https://github.com/spleenYou/OC-P13)

Le projet consiste à réduire la dette technique de l'application en modularisant l'app principale en trois modules.
Mise en place de Sentry pour suivre les erreurs.
Mise en place d'un pipeline CI/CD qui :
    - Vérifie le linting
    - Effectue les tests et vérifie que la couverture du code (minimum 80%)
    - Créer deux images Docker (une latest et une avec le tag GIT_COMMIT pour historique)
    - Envoie sur le hub Docker
    - Déploiement sur Render avec passage des variables d'environnement

Apprentissage :
- Docker
- Github Actions
- ReadTheDocs
- Render