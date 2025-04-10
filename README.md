# citationapp

# Projet Docker

Cette application affiche une citation aléatoire.

## 📦 Contenu du repo

- `docker-compose.yml` : orchestration des services frontend (React) et backend (Node.js).
- Les images Docker sont pré-construites et hébergées sur Docker Hub :
  - Backend : `josdocker339/backendquotes:latest`
  - Frontend : `josdocker339/frontendquotes:latest`

## 🚀 Lancer le projet

Assurez-vous d’avoir Docker Desktop installé.

```bash
git clone https://github.com/Joshua-dscops/citationapp.git
cd citationapp
docker-compose up
```

## Questions de réflexion

Quelle différence fais-tu entre un Dockerfile et un docker-compose.yml ?

Un Dockerfile définit l'environnement pour construire une image Docker, tandis que docker-compose.yml orchestre plusieurs services Docker dans un environnement multi-conteneurs.

Quels sont les avantages de séparer les services dans une architecture Docker ?

Séparer les services permet d'isoler les composants, de faciliter la scalabilité et la maintenance des conteneurs.

En quoi Docker Compose facilite-t-il le travail en équipe et le déploiement ?

Docker Compose permet de définir et partager des environnements cohérents, simplifiant la gestion des dépendances et le déploiement.

Pourquoi est-il utile de publier une image sur Docker Hub même pour un projet perso ?

Publier une image sur Docker Hub permet un accès facile, le partage et la réutilisation de l'image entre différentes machines et utilisateurs, même pour un projet personnel.
