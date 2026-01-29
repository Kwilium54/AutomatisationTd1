# Immo API PHP

API REST pour la gestion immobilière développée avec Slim 4 et MySQL.

## Prérequis

- Docker
- Docker Compose

## Installation

```bash
# Cloner le projet
git clone <url-repo>
cd cours1/immo-api-php

# Démarrer les containers
docker-compose up -d --build

# Installer les dépendances
docker-compose exec php-api composer install
```

## Accès

- API : http://localhost:8080
- Hello World : http://localhost:8080/

## Arrêter le projet

```bash
docker-compose down
```
