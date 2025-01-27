# Interface Client Vue.js

Interface client pour le projet immobilier, développée avec Vue.js.

## Prérequis

- Docker
- Docker Compose

## Installation

1. Construire et démarrer le conteneur :
```bash
docker-compose up -d
```

2. L'application sera accessible à l'adresse : http://localhost:8080

## Développement

1. Les modifications du code sont automatiquement prises en compte grâce au volume monté
2. Les logs peuvent être consultés avec :
```bash
docker-compose logs -f
```

## Tests

Pour exécuter les tests :
```bash
docker-compose exec vue-app npm run test
```

## Build pour la production

Pour créer une version de production :
```bash
docker-compose exec vue-app npm run build
```

## Configuration

L'application est configurée pour communiquer avec l'API à l'adresse : http://localhost:8000
Pour modifier cette configuration, ajustez la variable d'environnement `VITE_API_URL` dans le fichier `docker-compose.yml`.
