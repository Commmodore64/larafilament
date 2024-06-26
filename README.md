# Laravel 11 Filament Starter Kit

Este es un kit de inicio para Laravel 11 que incluye Filament, una interfaz de usuario para la administración de tu aplicación Laravel.

## Requisitos previos

Antes de comenzar, asegúrate de cumplir con los siguientes requisitos:

- PHP >= 8.0
- Composer instalado
- Node.js y NPM instalados (para compilar assets si es necesario)
- Una base de datos compatible (MySQL, PostgreSQL, SQLite, etc.)

## Instalación

1. Clona este repositorio en tu máquina local:

   ```bash
   git clone https://github.com/tu-usuario/laravel-filament-starter.git
   ```
## Navega al directorio del proyecto:
```
cd laravel-filament-starter
```

## Copia el archivo de configuración .env.example y renómbralo a .env:
Agregar las credenciales de tu base de datos
```
cp .env.example .env
```


## Ejecuta las migraciones para crear las tablas de la base de datos:

```
php artisan migrate
```
## Crear un usuario de Filament
Para acceder al panel de administración de Filament, necesitas crear un usuario. Puedes hacerlo ejecutando el siguiente comando:

```
php artisan make:filament-user
```
Este comando te guiará a través de la creación de un nuevo usuario para acceder al panel de administración de Filament.
