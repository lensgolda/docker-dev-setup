### Environment setup in docker for local development.

- Postgres (postgis/postgis:9.6-2.5)
  - available on localhost:5432
  - Saves DB data into directory ./data/postgres
- Redis (redis:alpine)
  - available on localhost:6379
- RabbitMQ + management (rabbitmq:3.8-management-alpine)
  - available on localhost:5672
  - management available on http://localhost:15672/

### Run with docker-compose up -d
