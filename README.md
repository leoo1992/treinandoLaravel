# Treinando Laravel

Projeto de estudo baseado no esqueleto Laravel 8, com autenticação inicial via Laravel Breeze e rotas para a página inicial e dashboard autenticado. O código atual mantém a estrutura padrão do framework.

## Stack
- PHP 7.3+ / 8.x
- Laravel 8
- Laravel Breeze e Sanctum
- Composer

## Como executar

```bash
composer install
cp .env.example .env
php artisan key:generate
php artisan serve
```

Configure o banco de dados no arquivo `.env` antes de executar as migrações.
