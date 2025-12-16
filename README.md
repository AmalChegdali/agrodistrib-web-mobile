# AgroDistrib - Application Web et Mobile pour le Secteur Agroalimentaire

Projet transversal : développement d'une application web et mobile dédiée au secteur agroalimentaire pour faciliter la distribution et la gestion des produits agricoles.

## 📋 Description

AgroDistrib est une solution complète développée dans le cadre d'un projet transversal, visant à moderniser et optimiser la distribution dans le secteur agroalimentaire. L'application offre une plateforme web et mobile permettant de connecter les producteurs, distributeurs et clients finaux, facilitant ainsi la gestion des stocks, des commandes et de la distribution des produits agricoles.

## 🎯 Objectifs du Projet

- **Digitaliser la chaîne de distribution** agroalimentaire
- **Faciliter la gestion des stocks** et des produits
- **Connecter les acteurs** du secteur (producteurs, distributeurs, clients)
- **Optimiser les processus** de commande et de livraison
- **Améliorer la traçabilité** des produits agricoles

## 🚀 Fonctionnalités Principales

### Application Web
- ✅ **Gestion des produits** : Ajout, modification et suppression de produits agricoles
- ✅ **Gestion des stocks** : Suivi en temps réel des stocks disponibles
- ✅ **Gestion des commandes** : Création et suivi des commandes
- ✅ **Tableau de bord** : Visualisation des statistiques et métriques clés
- ✅ **Gestion des utilisateurs** : Authentification et gestion des rôles
- ✅ **Interface responsive** : Design adaptatif pour tous les écrans

### Application Mobile
- ✅ **Application native** : Accès mobile aux fonctionnalités principales
- ✅ **Notifications** : Alertes pour les nouvelles commandes et mises à jour
- ✅ **Géolocalisation** : Suivi des livraisons en temps réel
- ✅ **Scan de produits** : Identification rapide via codes-barres/QR codes
- ✅ **Mode hors ligne** : Fonctionnalités disponibles sans connexion

## 🛠️ Technologies Utilisées

### Frontend Web
- **TypeScript** - Langage de programmation principal
- **HTML5 / CSS3** - Structure et style
- **Framework moderne** - Interface utilisateur réactive

### Application Mobile
- **TypeScript** - Développement cross-platform
- **Framework mobile** - Application native ou hybride

### Backend
- **API REST** - Architecture backend pour les services
- **Base de données** - Gestion des données persistantes

## 📁 Structure du Projet

```
AgroDistrib/
│
├── AgroDistrib-Mobile/          # Application mobile
│   ├── src/                    # Code source de l'application mobile
│   └── assets/                 # Ressources (images, icônes)
│
├── AgroDistrib_Front-main/     # Application web frontend
│   ├── src/                    # Code source TypeScript
│   ├── components/             # Composants réutilisables
│   ├── pages/                  # Pages de l'application
│   └── styles/                 # Fichiers CSS
│
├── MiniProjet-Back/            # Backend API
│   ├── controllers/            # Contrôleurs API
│   ├── models/                 # Modèles de données
│   ├── routes/                 # Routes API
│   └── services/              # Services métier
│
└── README.md                   # Documentation du projet
```

## 🚀 Installation et Configuration

### Prérequis

- **Node.js** (version 14 ou supérieure)
- **npm** ou **yarn**
- **TypeScript** (installé globalement ou localement)
- **Base de données** (selon le backend utilisé)

### Installation

1. **Cloner le dépôt**
   ```bash
   [git clone https://github.com/AmalChegdali/agrodistrib-web-mobile.git]
   cd agrodistrib-web-mobile
   ```

2. **Installer les dépendances du frontend web**
   ```bash
   cd AgroDistrib_Front-main
   npm install
   # ou
   yarn install
   ```

3. **Installer les dépendances de l'application mobile**
   ```bash
   cd AgroDistrib-Mobile
   npm install
   # ou
   yarn install
   ```

4. **Configurer le backend**
   ```bash
   cd MiniProjet-Back
   npm install
   # Configurer les variables d'environnement
   cp .env.example .env
   ```

5. **Lancer l'application**

   **Frontend Web :**
   ```bash
   cd AgroDistrib_Front-main
   npm start
   # ou
   yarn start
   ```

   **Backend :**
   ```bash
   cd MiniProjet-Back
   npm start
   # ou
   yarn start
   ```

   **Application Mobile :**
   ```bash
   cd AgroDistrib-Mobile
   npm start
   # Suivez les instructions pour lancer sur iOS/Android
   ```

## 📱 Utilisation

### Application Web
1. Accédez à l'application via votre navigateur
2. Connectez-vous avec vos identifiants
3. Naviguez dans les différentes sections :
   - **Produits** : Gérer le catalogue de produits
   - **Commandes** : Créer et suivre les commandes
   - **Stocks** : Consulter et mettre à jour les stocks
   - **Tableau de bord** : Visualiser les statistiques

### Application Mobile
1. Installez l'application sur votre appareil
2. Connectez-vous avec les mêmes identifiants
3. Utilisez les fonctionnalités mobiles :
   - Scanner les codes produits
   - Passer des commandes en déplacement
   - Recevoir des notifications
   - Suivre les livraisons

## 🔐 Sécurité

- Authentification sécurisée (JWT)
- Validation des données côté client et serveur
- Protection contre les injections SQL
- Chiffrement des données sensibles
- Gestion des permissions et rôles

## 🧪 Tests

```bash
# Tests unitaires
npm test

# Tests d'intégration
npm run test:integration

# Tests end-to-end
npm run test:e2e
```

## 📊 Fonctionnalités Avancées

- **Gestion multi-utilisateurs** : Différents rôles (admin, distributeur, client)
- **Notifications en temps réel** : Alertes pour les commandes et mises à jour
- **Rapports et statistiques** : Tableaux de bord analytiques
- **Export de données** : Génération de rapports (PDF, Excel)
- **Intégration de paiement** : Gestion des transactions
- **Géolocalisation** : Suivi GPS des livraisons

## 🤝 Contribution

Ce projet est un projet transversal académique. Pour toute question ou suggestion :

1. Ouvrez une issue pour signaler un bug ou proposer une fonctionnalité
2. Créez une branche pour vos modifications
3. Soumettez une pull request avec une description détaillée

## 📄 Licence

Ce projet est développé dans le cadre académique. Tous droits réservés.

## 👥 Équipe

**Amal Chegdali**

- GitHub: [@AmalChegdali](https://github.com/AmalChegdali)
- LinkedIn: [Amal Chegdali](https://www.linkedin.com/in/amal-chegdali-37a5b9239/)
- Email: a.chegdali@gmail.com

## 🙏 Remerciements

- Équipe pédagogique pour l'encadrement du projet transversal
- Communauté TypeScript et des frameworks utilisés
- Tous les contributeurs et ressources open-source

## 📚 Ressources

- [Documentation TypeScript](https://www.typescriptlang.org/docs/)
- [Guide de développement mobile](https://reactnative.dev/docs/getting-started)
- [Best practices REST API](https://restfulapi.net/)

## 🗺️ Roadmap

- [ ] Amélioration de l'interface utilisateur
- [ ] Ajout de fonctionnalités de paiement en ligne
- [ ] Intégration de l'IA pour la prédiction de la demande
- [ ] Application de gestion pour les producteurs
- [ ] Système de notation et avis
- [ ] Intégration avec des systèmes de logistique externes

---

⭐ Si ce projet vous a été utile, n'hésitez pas à lui donner une étoile !
