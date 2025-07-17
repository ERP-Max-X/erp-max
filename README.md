# ERP-Max

Мультисервісний ERP-проект для локального запуску через Docker.

## Структура:

- API Gateway: `graphql-gateway/`
- Tenant Service: `tenant-svc/`
- ERP Service: `erp-svc/`
- Сховище даних: `data/` (postgres, redis, rabbitmq)

## Як запустити:

1️⃣ Встановіть [Docker](https://www.docker.com/products/docker-desktop)

2️⃣ Клонувати репозиторій:

```bash
git clone https://github.com/yourusername/ERP-Max.git
cd ERP-Max
