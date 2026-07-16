# Chore: Multi-Stage Docker & Compose Orchestration

Created optimized multi-stage Dockerfiles to minimize production image sizes by 
excluding build-time dependencies, devTools, and package caches.

Configured a local `docker-compose.yml` file to spin up the application 
alongside its PostgreSQL database and Redis caching container.
