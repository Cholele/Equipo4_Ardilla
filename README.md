Crear un ambiente de desarrollo basico con Linux, Apache, Mysql y Php

https://builtin.com/articles/lamp-stack


Description

crear archivo de configuracion yml docker-compose.yml con imagenes para armar un ambiente lamp, cada elemento debe ser una imagen
L: Linux
A: Apache
M: Mysql
P: Php

podrán compartir imagen Linux, Apache y PHP
y la segunda imagen Linux, Mysql

o mantener cada una individual, en caso de Linux se repite en todas ya que es el sistema operativo base




Crear un archivo docker-compose.yml para desplegar un CMS (wordpress, joomla o drupal) con las siguientes características:

Volumen para cada servicio y un volumen compartido entre todos los servicios
Red interna aislada donde solo puedan comunicarse los servicios
Exponer unicamente el puerto del servicio del servidor de aplicaciones
Servicios requeridos:

Base de datos mysql
PHP FPM (revisar requerimientos minimos de la version php del cms)
Servidor de aplicaciones (apache2 o nginx)
Para el CMS elegido, deberá descargar los fuentes de la pagina oficial y mapearlo al servidor de aplicaciones (no usar imagen de docker hub para el cms)
