# SoufienEvaluation - Projet E5 DevSecOps

## Objectif
Déployer 4 applications conteneurisées avec Docker et orchestrées par docker-compose, avec reverse proxy Traefik.

## Applications
- Flask Soft Design (Stripe) ➜ reverse proxy
- Django Argon ➜ reverse proxy
- React Berry ➜ reverse proxy
- Static HTML/CSS ➜ accès direct

## Architecture
- Reverse Proxy : Traefik 2.10
- Réseau unique : web
- 4 services distincts

## Commandes
```bash
docker-compose build
docker-compose up
docker-compose down

Accès
http://flask.local

http://django.local

http://react.local

http://localhost:8080


Traefik Dashboard ➜ http://localhost:8081