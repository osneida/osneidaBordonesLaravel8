
## Sobre el Proyecto

Esta desarrollado con Laravel 8, use la plantilla laravel-adminlte, en este proyecto:



- [Autentificación de usuario]().
- [Página para enviar correo de contacto]().
- Al ejecutar las migraciones, se crea el usuario [admin@example.com] con password 123456789 .
- Se crean otros usuarios no administradores con clave "password" []().
- Se crean asigna roles a los usuarios []().
- Se puede crear, modificar, eliminar [post y categorías]().

## Pasos para instalar el Proyecto

1.- composer install  (comando de consola)

2.- npm install (comando de consola)

3.- renombra .env.example como .env

4- configurar Base de Datos y datos de Correo en .env

5.- ejecutar por consola:   php artisan migrate:fresh --seed

6.- composer require jeroennoten/laravel-adminlte (comando de consola)

7.- php artisan adminlte:install (comando de consola)

8.- reemplazar el archivo adjunto en la carpeta config (en el correo)

9.- php artisan serve (comando de consola)