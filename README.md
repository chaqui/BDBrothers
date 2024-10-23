# BD Brothers 

Sistema para gestionar la información de los hermanos de la iglesia.

## Requisitos
Para poder ejecutar el sistema es necesario tener instalado:
- Php 7.4
- Composer
- Node.js
- Npm
- Docker

## Ejecución
Para ejecutar el sistema es necesario seguir los siguientes pasos:
1. Clonar el repositorio
2. Instalar las dependencias de PHP con el comando `composer install`
3. Instalar las dependencias de Node.js con el comando `npm install`
4. Crear el archivo `.env` a partir del archivo `.env.example` y configurar las variables de entorno
5. Ejecutar el comando `php artisan key:generate`
6. Ejecutar el comando `php artisan migrate`
7. Ejecutar el comando `php artisan db:seed`

## Ejecucion con Docker
Para ejecutar el sistema con Docker es necesario seguir los siguientes pasos:
1. Clonar el repositorio
2. Crear el archivo `.env` a partir del archivo `.env.example` y configurar las variables de entorno
3. Ejecutar el comando `docker-compose up -d`
