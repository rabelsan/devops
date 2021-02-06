# devops
Práctica configuración de servidores y despliegue de aplicaciones
## Ejercicio 1: Backend con Node


**URL**

- https://nodepop.rbsdevops.com


La aplicación **node** se ha desplegado sobre **nginx** como proxy inverso y servidor de estáticos

**Supervisor** gestiona dos procesos:

- nodepop: La propia aplicación node

- thumbService: Servicio que atiende peticiones para reducir el tamaño de imágenes

La base de datos utilizada es **mongo** y, por seguridad, requiere autenticación (authorization: enabled)

También se ha implementado el protocolo https medieante **lets encrypt** y **certbot**

**API** nodepop

- https://nodepop.rbsdevops.com/apiDoc/index.html

## Ejercicio 2: Backend con React-redux

**URL**

http://3.141.69.22 (o también http://rbsdevops.com). Para acceder a la demo se puede utilizar el email: user@example.com / pwd: 1234.

Para desplegar la aplicación **react** se han implementado un segundo backend (el api es diferente al anterior), y el propio frontend

El frontend está desplegado sobre **nginx**

El backend, se maneja desde **supervisor** para asegurar que siempre esté operativo

Igualmente, la base de datos es **mongo** y también requiere autenticación

Los estáticos de las imágenes los sirve **nginx** en lugar de **express**
## Resources:

- https://aws.amazon.com/es/
- https://www.nginx.com/blog/websocket-nginx/
- http://supervisord.org/introduction.html
- https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/
- https://letsencrypt.org/
- https://certbot.eff.org/

