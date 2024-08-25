## About Laravel 11 Playground

Laravel 11 Playground is asimple Job Board platform built using the latest version of the framework (at that time).

This is based on Jeffrey Way's [30 Days to Learn Laravel](https://laracasts.com/series/30-days-to-learn-laravel-11) series on Laracasts

## Requirements

- PHP installed
- NodeJS and NPM installed

## Setup

1. Clone this repository
```shell
git clone https://github.com/ryturiaga-arcanys/laravel-11-playground
```
2. Install backend dependencies
```shell
composer install
```
3. Copy environment variables
```shell
cp .env.example .env
```
4. Generate application key
```shell
php artisan key:generate
```
5. Create SQLite database
```shell
touch database/database.sqlite
```
6. Migrate tables and seed data
```shell
php artisan migrate --seed
```
7. Install frontend dependencies
```shell
npm install
```
8. Build scripts and stylesheets
```shell
npm run build
```
9. Run local server
```shell
php artisan serve
```
