# Bitrix Docker Stack

A complete Docker-based development environment for Bitrix CMS.

This stack provides a ready-to-use setup for local development with all required services:

- Apache + PHP 8.2
- Nginx reverse proxy
- MariaDB database
- RabbitMQ message broker
- Docker Compose orchestration

## Features

- Ready-to-run Bitrix development environment
- Support for .htaccess and mod_rewrite
- Custom Apache configuration
- Persistent MariaDB storage
- Easy service management with Docker Compose

## Services

| Service | Description |
|--------|-------------|
| Apache | PHP 8.2 + Bitrix runtime |
| Nginx | Reverse proxy |
| MariaDB | Database server |
| RabbitMQ | Message broker for Bitrix |

## Start the environment

```bash
docker compose up -d --build
```

## host -> http://localhost:8080
## RabbitMQ host -> http://localhost:15672

## stop the  environment
```bash
docker compose down
```