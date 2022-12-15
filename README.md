# Práctica 5 - Despliegue con docker-compose

🔊 Recomendaciones básicas:

* _Desplegar apache en último lugar. Puede generar problemas con el puerto, impidiendo que otra aplicación use el puerto usado incluso cuando se ha eliminado el contenedor y la imagen de apache._
* _Parar las otras aplicaciones si usan el mismo puerto o cambiar los puertos para que sean diferentes._

## Wordpress 📄

* Descarga la carpeta wordpress.
* En visual studio code abre la carpeta.
* Abre un terminal y ejecuta el comando docker-compose -d
* Abre en el navegador.

📌 Fuente: https://hub.docker.com/_/wordpress

## Adminer 📜

* Descarga la carpeta adminer.
* En visual studio code abre la carpeta.
* Abre un terminal y ejecuta el comando docker-compose -d
* Abre en el navegador.

📌 Fuente: https://hub.docker.com/_/adminer

## Guestbook 📰

* Descarga la carpeta guestbook.
* En visual studio code abre la carpeta.
* Abre un terminal y ejecuta el comando docker-compose -d
* Abre en el navegador.

📌 Fuente: https://josedom24.github.io/curso_docker_2022/sesion4/guestbook.html

## MediaWiki 📃

* Descarga la carpeta mediawiki.
* En visual studio code abre la carpeta.
* Abre un terminal y ejecuta el comando docker-compose -d
* Abre en el navegador.
* Para conectar la base de datos usa la ip que aparece en el documento resultante de hacer click con el botón derecho, inspect en el contenedor de la base de datos.

```
 usuario: wikiuser
 contraseña: example

```
* Sigue los pasos del navegador. Utliza la opción: Ya me aburrí, para simplificar los pasos.
* Descarga el documento LocalSettings.php y copialo en la carpeta mediawiki.
* Abre el documento docker-compose.yml t descomenta la siguiente línea:

```
  # - ./LocalSettings.php:/var/www/html/LocalSettings.php
```
* En el terminal, sin parar los contenedores, ejecuta el comando docker-compose -d
* Abre el navegador

📌 Fuente: https://hub.docker.com/_/mediawiki
