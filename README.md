# 🚀 Laravel Starter Template with Sail, Docker, FrankenPHP, and Ngrok

This is a Laravel starter template that comes pre-integrated with Sail, Docker, FrankenPHP, and Ngrok.

## How to install
1. **Clone repository**
```bash
git clone https://github.com/Karungg/laravel-11-frankenphp-ngrok.git
cd laravel-11-frankenphp-ngrok
```
2. **Install dependencies using composer**
```
composer install
```
4. **Copy the .env file**
```
cp .env.example .env
```
5. **Configure the environment variables in the .env file**
```
DB_CONNECTION=
DB_HOST=
DB_PORT=
DB_DATABASE=
DB_USERNAME=
DB_PASSWORD=
```
6. Build application
```
sail build #if you're using sail docker
docker compose up #if you're using docker compose
```
