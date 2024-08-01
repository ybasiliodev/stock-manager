# Stock Manager

CRUD utilizando laravel para simular um controle de estoque




## Instalação

```bash
  cp stock-app/.env.example stock-app/.env
  docker compose build
  docker compose up -d
  docker exec php-server php artisan config:cache
  docker exec php-server php artisan migrate
```
