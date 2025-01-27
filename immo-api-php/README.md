# API Immobilier PHP

API backend pour le projet immobilier, développée avec PHP.

## Prérequis

- Docker
- Docker Compose

## Installation

1. Construire et démarrer les conteneurs :
```bash
docker-compose up -d
```

2. L'API sera accessible à l'adresse : http://localhost:8000

## Services disponibles

- API PHP : http://localhost:8000
- PHPMyAdmin : http://localhost:8080
  - Utilisateur : user
  - Mot de passe : password

## Base de données

- Host : mysql
- Database : immobilier
- Username : user
- Password : password

## Développement

1. Les modifications du code sont automatiquement prises en compte grâce au volume monté
2. Les logs peuvent être consultés avec :
```bash
docker-compose logs -f
```

## Tests

Pour exécuter les tests :
```bash
docker-compose exec php ./vendor/bin/phpunit
```
