# Proxy inverso

Para hacer esta práctica vamos a utilizar el siguiente [escenario](https://fp.josedomingo.org/serviciosgs/u08/doc/haproxy/vagrant.zip) en vagrant.

En este caso queremos instalar dos servidores web en el apache1 y en apache2, estos servidores deben servir una web completa (con hoja de estilo, imágenes,…) busca alguna plantilla (debe tener algunas páginas html para probar los enlaces).

Configura en el ordenador balanceador (tienes que detener haproxy) un proxy inverso para acceder a las aplicaciones de dos formas distintas:

## Tarea 1

Para que se acceda a la primera aplicación con la URL `www.app1.org` y a la segunda aplicación con la URL `www.app2.org`.

## Tarea 2

Para que se acceda a la primera aplicación con la URL `www.servidor.org\app1` y a la segunda aplicación con la URL `www.servidor.org\app2`.