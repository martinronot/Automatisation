Martin RONOT RA-DWM

# Projet Automatisation

Ce repository contient trois projets distincts :

1. `immo-api-php` : API backend en PHP
2. `immo-admin-react` : Interface d'administration en React
3. `immo-client-vue` : Interface client en Vue.js

## Structure du Projet

Le projet est organisé selon les principes GitFlow avec les branches suivantes :
- `main` : Production
- `develop` : Développement
- `feature/*` : Fonctionnalités en cours de développement

## Prérequis

- Docker
- Docker Compose
- Git

## Installation

Chaque projet dispose de son propre fichier docker-compose et README. Suivez les instructions spécifiques dans chaque dossier de projet.

### Configuration Globale

1. Cloner le repository :
```bash
git clone https://github.com/martinronot/Automatisation.git
cd Automatisation
```

2. Lancer les services :
```bash
docker-compose up -d
```

## Projets

### API PHP
- Port : 8000
- Base de données MySQL
- Documentation détaillée dans `immo-api-php/README.md`

### Admin React
- Port : 3000
- Documentation détaillée dans `immo-admin-react/README.md`

### Client Vue.js
- Port : 8080
- Documentation détaillée dans `immo-client-vue/README.md`

## Contribution

1. Créer une nouvelle branche feature :
```bash
git checkout develop
git checkout -b feature/nom-de-la-fonctionnalite
```

2. Développer la fonctionnalité

3. Créer une Pull Request vers la branche develop
