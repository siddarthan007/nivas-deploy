# Nivas PMS — Quick Start

Run the full stack with one command.

## Prerequisites
- Docker 24+ with Docker Compose v2
- 4 GB RAM minimum

## Setup (2 minutes)

1. Download this repo (or just `docker-compose.quickstart.yml` + `.env.docker.example`)
2. `cp .env.docker.example .env.docker`
3. Edit `.env.docker` — set passwords, JWT secret, and your domain
4. `docker compose -f docker-compose.quickstart.yml --env-file .env.docker up -d`
5. Open `http://localhost` — login with `[EMAIL_ADDRESS]` + your `[SUPER_ADMIN_PASSWORD]`