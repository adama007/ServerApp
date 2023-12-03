# ServerApp

## Description

Ce projet a pour objectif de créer une plateforme de gestion des serveurs, offrant la possibilité d'activer et de désactiver les serveurs en fonction de leur statut de ping.
La solution utilise une architecture API REST avec Spring Boot en Java pour le backend et Angular pour le frontend. Les données sont stockées de manière persistante dans une base de données MySQL.

## Outils Utilisés

- **Spring Boot :** Framework Java pour le développement d'applications backend.
- **Angular :** Framework JavaScript/TypeScript pour la création d'applications frontend.
- **MySQL :** Système de gestion de base de données relationnelles.
- **Git :** Système de contrôle de version pour le suivi des modifications du code source.
- **Maven :** Outil de gestion de projet et de construction pour Java.
- **npm :** Gestionnaire de paquets pour JavaScript/Node.js.

## Fonctionnalités Principales

- **Activation et Désactivation des Serveurs :** Les utilisateurs peuvent activer ou désactiver les serveurs en fonction de la disponibilité constatée grâce à des requêtes de ping.

- **Vérification du Statut par Ping :** Le système utilise des requêtes de ping pour évaluer en temps réel le statut de chaque serveur.

- **Interface Utilisateur Intuitive :** L'interface utilisateur développée en Angular offre une expérience conviviale pour une gestion simple et efficace des serveurs.

- **API RESTful avec Spring Boot :** Le backend utilise Spring Boot pour créer une API RESTful, permettant aux clients frontend (Angular) d'interagir avec les fonctionnalités du serveur.

- **Base de Données MySQL :** La persistance des données est assurée par une base de données MySQL, stockant les informations relatives aux serveurs et à leur statut.

## Installation

1. Clonez le dépôt du projet.
   ```bash
   git clone https://github.com/votre-utilisateur/gestion-serveurs.git
   
## Base de donnés
Ouvrez le fichier application.properties dans le dossier /backend/src/main/resources et configurez les paramètres de connexion à votre base de données MySQL.
# /backend/src/main/resources/application.properties

## Utilisation
Lancez le backend Spring Boot en utilisant votre IDE ou la commande Maven.

   cd backend
   mvn spring-boot:run
   

Lancez le frontend Angular.

  cd frontend
  ng serve
Ouvrez l'application dans votre navigateur à l'adresse http://localhost:4200.

Explorez les fonctionnalités de gestion des serveurs via l'interface utilisateur.

Contribution
Les contributions sont les bienvenues! Consultez le fichier CONTRIBUTING.md pour plus d'informations sur la façon de contribuer au projet.



