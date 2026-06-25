# FamilyEventPlanner
Family Event Planner
<p align="center"> <img src="./docs/logo-2.png" alt="Family Event Planner Logo" width="250"> </p>
Présentation
Family Event Planner est une application web permettant aux familles et groupes d'amis d'organiser facilement leurs événements privés.
L'application centralise l'ensemble des échanges autour d'un événement :
Création d'événements
Gestion des invités
Répartition des contributions
Tableau de bord de suivi
Messagerie collaborative
Gestion des présences
Le projet a été conçu dans une approche Full Stack moderne avec une architecture REST, un frontend Angular et un backend Java Spring Boot.
Aperçu de l'application
Page d'accueil
<p align="center"> <img src="./docs/Accueil.jpeg" alt="Accueil" width="900"> </p>
La page d'accueil présente les fonctionnalités principales de la plateforme et permet à un utilisateur de créer ou rejoindre un événement.
Dashboard Organisateur
<p align="center"> <img src="./docs/dashboad.jpeg" alt="Dashboard" width="900"> </p>
Le tableau de bord permet à l'organisateur de :
gérer ses événements ;
suivre les réponses des invités ;
consulter les contributions ;
communiquer avec les participants.
Fonctionnalités
Organisateur
Création d'événements
Modification des informations
Gestion des participants
Gestion des contributions
Consultation des statistiques de participation
Messagerie
Invité
Consultation d'un événement
Confirmation de présence
Proposition d'une contribution
Participation aux échanges
Contributions collaboratives
Les participants peuvent indiquer ce qu'ils apportent :
Boissons
Desserts
Entrées
Vaisselle
Matériel
L'objectif est d'éviter les doublons et de faciliter l'organisation.
Architecture technique
Stack utilisée
Backend
Java 21
Spring Boot 3
Spring Security
Spring Data JPA
Hibernate
JWT
Frontend
Angular 20
TypeScript
Angular Router
RxJS
Base de données
PostgreSQL
Supabase
DevOps
Docker
GitHub Actions
Terraform
Google Cloud Platform (GCP)
Modèle de données
Schéma de base de données
<p align="center"> <img src="./docs/supabase-schema-zyzkvoegjwfzkxmnbkyz.png" alt="BDD" width="1000"> </p>
Le modèle de données a été conçu autour des principales entités métier :
User
Event
Invitation
Contribution
Message


Intégration Continue (CI)
Pipeline GitHub Actions
<p align="center"> <img src="./docs/build-and-deploy.png" alt="CI/CD" width="900"> </p>
Le projet dispose d'un pipeline GitHub Actions permettant :
Build automatique
Exécution des tests
Vérification de la qualité du code
Préparation du déploiement
Cette automatisation garantit que chaque modification respecte les critères de qualité définis.
Infrastructure as Code
Provisionnement Terraform
<p align="center"> <img src="./docs/terraform.png" alt="Terraform" width="900"> </p>
L'infrastructure est gérée via Terraform afin de :
versionner l'infrastructure ;
automatiser les déploiements ;
assurer la reproductibilité des environnements.
Le projet inclut notamment :
Configuration du provider GCP
Gestion des variables d'environnement
Déploiement automatisé des ressources cloud
Sécurité
Authentification JWT
Gestion des rôles
Validation des entrées utilisateur
Protection des endpoints REST
Gestion sécurisée des variables sensibles
Perspectives d'évolution
Notifications temps réel via WebSocket
Envoi d'emails automatiques
Calendrier partagé
Génération de listes de courses
Application mobile
Compétences démontrées
Développement
Java 21
Spring Boot
Angular 20
REST API
PostgreSQL
DevOps
Docker
GitHub Actions
Terraform
Google Cloud Platform
Architecture
Architecture multicouche
Séparation des responsabilités
Gestion des dépendances
Sécurisation d'API REST
Auteur
Daniel LANDALLY
Développeur Full Stack Java / Spring Boot & Angular
Projet personnel réalisé dans une démarche de montée en compétences sur les pratiques modernes de développement logiciel, d'architecture applicative et de DevOps.

