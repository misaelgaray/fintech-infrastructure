# Services for fintech spark project

### Start Services
docker-compose up -d

### REQUIRED: restar kafka exporter
docker compose restart kafka-exporter

docker compose logs prometheus

### Down services
docker-compose down