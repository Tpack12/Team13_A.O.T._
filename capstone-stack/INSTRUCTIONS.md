# Capstone Docker Stack

## What this is
This project runs:
- SillyTavern (AI frontend)
- n8n (automation workflows)

Both are containerized using Docker Compose.

---

## Requirements
- Docker Desktop installed and running

---

## Setup

1. Clone the repo:
   git clone https://github.com/Tpack12/Team13_A.O.T._.git

2. Go into the folder:
   cd capstone-stack

3. Create your environment file:
   cp .env.example .env

4. Start everything:
   docker compose up -d

---

## Access the apps

- SillyTavern: http://localhost:8000
- n8n: http://localhost:5678

---

## Stop everything

docker compose down
