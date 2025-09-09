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

- **POST /api/todos — Ajouter une tâche**

- **PUT /api/todos/:id — Modifier une tâche**

- **DELETE /api/todos/:id — Supprimer une tâche**
  
<img width="1077" height="730" alt="do1" src="https://github.com/user-attachments/assets/3e3cb0dc-91fd-490c-86ee-a0e924589932" />
<img width="1035" height="785" alt="do2" src="https://github.com/user-attachments/assets/d2326c67-e312-48e2-b5f2-49fb0c6ae279" />
<img width="1031" height="791" alt="do3" src="https://github.com/user-attachments/assets/97adbdba-5d02-4d34-98fd-b6b6b31930ec" />
<img width="1077" height="672" alt="do5" src="https://github.com/user-attachments/assets/280db755-2acb-4e86-8fd8-c6cfcf5237c7" />

### Technologies utilisées

- **Node.js, Express**

- **MongoDB**

- **Docker, Docker Compose**
