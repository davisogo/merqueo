# merqueo
Simular registro, login

Observación: Adjutno el archivo merqueo.txt que contiene los caracteres, hay un delimitador que esuna comma, para poder leer cada cadena, eso fue lo que se me ocurrió en ese momento.

# Pasos para correr el proyecto
1. Descargar el zip adjunto
2. crear base de datos con nombre: "merqueo" Y correr las lineas de artisan para la migración:

php artisan migrate:install
php artisan migrate --force


Ejecutar en el navegador:

http://localhost/merqueo/public/cms 

Allí puedes loguearte o regustrarte, dependiendo si no hay sesión
