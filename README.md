# WebChatApp
Application web de messagerie

**WebChatApp** est une application web de messagerie permettant aux utilisateurs de communiquer entre eux via des messages texte.  
Elle repose sur une architecture **Node.js / Express.js** pour le backend et utilise **Sequelize** pour interagir avec une base de données **PostgreSQL**.

---

## 🚀 Fonctionnalités principales

- **Envoi et réception de messages** entre utilisateurs.  
- **Groupes de discussion** pour des conversations collectives.  
- **Authentification et autorisation** via un middleware sécurisé.  
- **API RESTful** pour l’interaction avec le frontend.  
- **Documentation API** générée automatiquement avec Swagger.  
- **Sécurité renforcée** grâce à Helmet.

---

## Technologies utilisées

| Technologie | Rôle |
|--------------|------|
| **Node.js** | Environnement d’exécution JavaScript côté serveur |
| **Express.js** | Framework web minimaliste et rapide |
| **Sequelize** | ORM pour interagir avec la base PostgreSQL |
| **PostgreSQL** | Système de gestion de base de données relationnelle |
| **Helmet** | Middleware de sécurité HTTP |
| **Swagger** | Génération de documentation d’API interactive |

---

##  Structure du projet

WebChatApp/
├── app.js # Fichier principal du serveur Express
├── models/
│ ├── messages.js # Modèle Sequelize pour les messages
│ ├── users.js # Modèle Sequelize pour les utilisateurs
│ └── groups.js # Modèle Sequelize pour les groupes
├── routes/ # Définitions des routes API
├── middlewares/ # Gestion des erreurs et authentification
├── util/ # Utilitaires (logger, etc.)
└── README.md

yaml
Copy code

---

## Installation et exécution

1. **Cloner le projet :**
   ```bash
   git clone https://github.com/JuniorKologne/WebChatApp.git
   cd WebChatApp
Installer les dépendances :

- npm install
- Configurer la base de données :

Lancer l’application :
- npm start

Accéder à la documentation Swagger :
- http://localhost:3000/doc

 Points clés
- Gestion des erreurs via un middleware dédié pour des réponses uniformes.

- Sécurité renforcée avec Helmet et une gestion stricte des en-têtes HTTP.

- Architecture modulaire facilitant la maintenance et l’évolution.

- Routage clair et découplé pour les différentes API de l’application.


