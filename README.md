# gitlab-matrix-integration-docker
🐳 Stack Docker Compose complète pour l'intégration GitLab-Matrix via le bridge Hookshot. Recevez les notifications GitLab directement dans vos salons Matrix avec Synapse, Element, GitLab CE et GitLab Runner.

## 🚀 Fonctionnalités

- **GitLab CE** - Instance GitLab auto-hébergée
- **Synapse** - Serveur Matrix homeserver
- **Element** - Client web Matrix
- **Hookshot** - Bridge GitLab-Matrix
- **GitLab Runner** - Intégration runner CI/CD
- **Docker Compose** - Déploiement en une commande

## 🛠️  Ce qui est inclus

- Serveur Matrix Synapse (localhost:8008)
- Client web Element (localhost:8080)
- GitLab Community Edition (localhost:8090)
- GitLab Runner pour CI/CD
- Bridge Hookshot pour les notifications en temps réel

## 📋 Démarrage rapide

1. Cloner ce dépôt
2. Suivre les instructions de configuration dans la documentation

## 🎯 Cas d'usage

- Équipes de développement souhaitant recevoir les notifications GitLab dans Matrix
- Intégration GitLab + Matrix auto-hébergée
- Apprentissage de Docker Compose avec des services réels
- Notifications de pipeline CI/CD dans les salons de discussion
