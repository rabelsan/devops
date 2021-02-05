# devops
Práctica configuración de servidores y despliegue de aplicaciones
## Ejercicio 1: Backend con Node


**URL**

- http://nodepop.rbsdevops.com


La aplicación **node** se ha desplegado sobre **nginx** como proxy inverso y servidor de estáticos

**Supervisor** gestiona dos procesos:

- nodepop: La propia aplicación node

- thumbService: Servicio que atiende peticiones para reducir el tamaño de imágenes

```
La base de datos utilizada es **mongo** y, por seguridad, requiere autenticación (authorization: enabled)
```
**API** nodepop

- http://nodepop.rbsdevops.com/apiDoc/index.html

## Ejercicio 2: Backend con React-redux

## Resources:

- https://aws.amazon.com/es/
- https://www.nginx.com/blog/websocket-nginx/
- http://supervisord.org/introduction.html
- https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/
- https://letsencrypt.org/
- https://certbot.eff.org/

