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
git clone https://github.com/taraschubarko/erp-max.git
cd ERP-Max

git clone https://github.com/taraschubarko/erp-max-tenant-svc.git

git clone https://github.com/taraschubarko/erp-max-erp-svc.git

git clone https://github.com/taraschubarko/erp-max-graphql-gateway.git
````
3️⃣ Створи папки

    data/redis
    data/postgres
    data/rabbitmq

4️⃣ Запусти команду

    docker-compose up --build

