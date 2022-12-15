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
