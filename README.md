# Proyecto Final curso FullStack

Este proyecto académico está diseñado para la gestión de proyectos ambientales, utilizando una base de datos MySQL y un stack tecnológico que incluye Node.js para el backend, y Tailwind CSS junto con Bootstrap para el frontend. La iniciativa se enmarca dentro del programa Talent Tech de MinTIC en Colombia.

Descripción del Proyecto
El sistema de manejo de proyectos ambientales tiene como objetivo facilitar la planificación, ejecución, seguimiento y reporte de proyectos enfocados en la conservación, gestión ambiental y las comunidades a su alrededor. Los usuarios del sistema pueden ser administradores, gestores de proyectos y miembros del equipo de proyecto. Las principales funcionalidades incluyen:

-Gestión de Usuarios: Registro, autenticación y gestión de roles.
-Gestión de Proyectos: Creación, actualización y seguimiento de proyectos.
-Reportes: Generación de reportes detallados sobre el estado y avance de los proyectos.
-Alertas y Notificaciones: Sistema de notificaciones para eventos importantes dentro de los proyectos.

Estructura del Proyecto

-Backend - Node.js con MySQL
-Node.js: Plataforma de desarrollo de aplicaciones del lado del servidor.
-Express.js: Framework web para Node.js.
-MySQL: Sistema de gestión de bases de datos relacional.

Frontend - Tailwind CSS y Bootstrap
-Tailwind CSS: Framework de CSS para diseño de interfaces modernas y personalizables.
-Bootstrap: Framework CSS para el desarrollo rápido y responsivo de aplicaciones web.

## Instalación

1. Clona el repositorio: `git clone https://github.com/DiegoQuevedoTIC/bioguardian.git`
2. Instalar gestor de paquetes: `composer install`
3. Instala las dependencias: `npm install` and `npm install` and `npm run build` and `npm run dev`
4. Migrar base de datos: `php artisan migrate`
5. Enjoy

## Configuración

1. Crea un archivo de configuración `.env` lista de variables de ambiente necesarias

APP_NAME=BioGuard
APP_ENV=local
APP_KEY=base64:hJrRVh+sWl+vwQsyABF8t3lt8EMO0jnZ9ntEumDQfDE=
APP_DEBUG=true
APP_URL=http://localhost

LOG_CHANNEL=stack
LOG_DEPRECATIONS_CHANNEL=null
LOG_LEVEL=debug

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=bio
DB_USERNAME=root
DB_PASSWORD=Banco123\*

BROADCAST_DRIVER=log
CACHE_DRIVER=file
FILESYSTEM_DISK=local
QUEUE_CONNECTION=sync
SESSION_DRIVER=file
SESSION_LIFETIME=120

MEMCACHED_HOST=127.0.0.1

REDIS_HOST=127.0.0.1
REDIS_PASSWORD=null
REDIS_PORT=6379

MAIL_MAILER=smtp
MAIL_HOST=mailpit
MAIL_PORT=1025
MAIL_USERNAME=null
MAIL_PASSWORD=null
MAIL_ENCRYPTION=null
MAIL_FROM_ADDRESS="hello@example.com"
MAIL_FROM_NAME="${APP_NAME}"

AWS_ACCESS_KEY_ID=
AWS_SECRET_ACCESS_KEY=
AWS_DEFAULT_REGION=us-east-1
AWS_BUCKET=
AWS_USE_PATH_STYLE_ENDPOINT=false

PUSHER_APP_ID=
PUSHER_APP_KEY=
PUSHER_APP_SECRET=
PUSHER_HOST=
PUSHER_PORT=443
PUSHER_SCHEME=https
PUSHER_APP_CLUSTER=mt1

VITE_PUSHER_APP_KEY="${PUSHER_APP_KEY}"
VITE_PUSHER_HOST="${PUSHER_HOST}"
VITE_PUSHER_PORT="${PUSHER_PORT}"
VITE_PUSHER_SCHEME="${PUSHER_SCHEME}"
VITE_PUSHER_APP_CLUSTER="${PUSHER_APP_CLUSTER}"

2. Agrega las configuraciones necesarias como las credenciales de la base de datos y cualquier otra información sensible.

## Uso

Ejecuta el proyecto con el siguiente comando:

```php artisan serve

```

El servidor estará disponible en [http://localhost:8000](http://localhost:8000).

## Estructura del Proyecto

Describe la estructura de directorios del proyecto y la funcionalidad de cada uno.

app/: Contiene el código de la aplicación, organizado en varios subdirectorios:

Console/: Comandos de consola personalizados.
Exceptions/: Manejo de excepciones.
Http/: Controladores, middleware y solicitudes HTTP.
Controllers/: Controladores de la aplicación.
Middleware/: Middleware de la aplicación.
Models/: Modelos Eloquent.
Providers/: Proveedores de servicios de la aplicación.
bootstrap/: Contiene el archivo app.php que arranca el framework y una carpeta cache para el almacenamiento en caché de archivos bootstrap.

config/: Archivos de configuración para los diversos componentes del framework.

database/: Migraciones, seeders y factories de la base de datos.

migrations/: Archivos de migración de la base de datos.
seeders/: Archivos de seeders para poblar la base de datos.
factories/: Archivos de factories para generar datos de prueba.
public/: Contiene el punto de entrada para todas las solicitudes al framework (index.php), así como los archivos de recursos públicos como CSS, JavaScript e imágenes.

resources/: Recursos de vistas y archivos de idioma.

views/: Vistas Blade.
lang/: Archivos de localización.
css/ y js/: Archivos CSS y JavaScript para la aplicación.
routes/: Archivos de definición de rutas de la aplicación (web.php, api.php, console.php, channels.php).

storage/: Archivos generados por el framework y subidas de usuarios.

app/: Subidas y archivos generados por la aplicación.
framework/: Cachés de framework y sesiones.
logs/: Archivos de log de la aplicación.
tests/: Pruebas automatizadas para la aplicación.

Feature/: Pruebas de características.
Unit/: Pruebas unitarias.
vendor/: Dependencias de Composer.

Archivos Raíz:

.env: Archivo de configuración del entorno.
artisan: Consola de comandos de Laravel.
composer.json: Archivo de configuración de Composer.

## Author

Diego Andres Quevedo Perez
Cel 3142945549
Siam Software Design\_
