# ERP-Max

Мультисервісний ERP-проект для локального запуску через Docker.

## Структура: Back-End

- API Gateway: `graphql-gateway/`
- Tenant Service: `tenant-svc/`
- ERP Service: `erp-svc/`
- Сховище даних: `data/` (postgres, redis, rabbitmq)

## Структура: Front-End
- API Gateway: `erp-front/`

## Як запустити:

1️⃣ Встановіть [Docker](https://www.docker.com/products/docker-desktop)

2️⃣ Клонувати репозиторій:

```bash
git clone https://github.com/ERP-Max-X/erp-max.git
cd ERP-Max

git clone https://github.com/ERP-Max-X/tenant-svc.git

git clone https://github.com/ERP-Max-X/erp-svc.git

git clone https://github.com/ERP-Max-X/graphql-gateway.git

git clone https://github.com/ERP-Max-X/erp-front.git
````
3️⃣ Створи папки

    data/redis
    data/postgres
    data/rabbitmq

4️⃣ Запусти команду

    docker-compose up --build

