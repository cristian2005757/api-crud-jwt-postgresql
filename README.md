# API CRUD JWT + PostgreSQL (Laravel)

API REST construida con Laravel que implementa autenticación con JWT usando `tymon/jwt-auth` y base de datos PostgreSQL.
Incluye endpoints de registro, login, obtención del usuario autenticado, logout y refresh de token.

## Tecnologías
- Laravel
- PostgreSQL
- JWT (tymon/jwt-auth)

## Funcionalidades
- ✅ Register (crea usuario y retorna token)
- ✅ Login (retorna token JWT)
- ✅ Me (ruta protegida, devuelve el usuario autenticado)
- ✅ Logout
- ✅ Refresh token

## Requisitos
- PHP 8.2+
- Composer
- PostgreSQL

## Instalación
```bash
git clone git clone https://github.com/cristian2005757/api-crud-jwt-postgresql.git
cd TU_REPO
composer install
cp .env.example .env
php artisan key:generate
php artisan jwt:secret
