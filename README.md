
# 🚀 Portfolio Infrastructure

Infrastructure Docker pour architecture microservices.

## 🧱 Services
- Traefik (API Gateway HTTPS)
- Auth Service
- PostgreSQL
- MinIO
- Prometheus
- Grafana

## ▶️ Lancer en dev
docker compose \
  -f docker-compose.yml \
  -f docker-compose.dev.yml \
  up --build

## ▶️ Lancer en prod
docker compose \
  -f docker-compose.yml \
  -f docker-compose.prod.yml \
  up -d
