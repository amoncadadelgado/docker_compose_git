#Descripción del contenido del docker-compose.yml#

* version: '2' Especifica que la versión del docker-compose es la 2.

* services: A partir de aqui empiezan las declaraciones.

* asir2a_git: Nombre del contenedor.

* image: internetsystemsconsortium/bind9:9.16 Nombre de la imagen que se va a crear.

* ports: Puertos que se van a utilizar. En nustro caso "5353:53".

* volumes: Volumenes que van a utilizar y asociados a las carpetas.
etc:/etc/bind
cache:/var/cache/bind
lib:/var/lib/bind
log:/var/log
* volumes: Creación de los volumenes
  etc: 
  cache:
  lib:
  log:
