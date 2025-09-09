# ToDo App Backend

Backend Node.js + Express pour gérer une application ToDo avec MongoDB, dockerisé.

---

## Fonctionnalités

- API REST pour créer, lire, modifier et supprimer des tâches (ToDos)
- Base de données MongoDB intégrée via Docker
- Conteneurisé avec Docker et Docker Compose pour un déploiement facile

---

## Installation

1. Cloner le dépôt

```bash
git clone https://github.com/Feriel-Barira/Backend-dockeris-ToDo-app.git
cd ton-projet
```

2. Lancer l’application avec Docker Compose
```bash
docker-compose up --build
```
### Routes principales
- **GET /api/todos — Liste des tâches**

-POST /api/todos — Ajouter une tâche

-PUT /api/todos/:id — Modifier une tâche

-DELETE /api/todos/:id — Supprimer une tâche

### Technologies utilisées

Node.js, Express

MongoDB

Docker, Docker Compose
