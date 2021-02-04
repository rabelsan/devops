# devops
Práctica configuración de servidores y despliegue de aplicaciones
## Ejercicio 1: Backend con Node

URL```
- http://nodepop.rbsdevops.com
```
Se ha desplagado la aplicación node sobre nginx como proxy inverso y servidor de estático

Supervisor gestiona dos procesos:
## nodepop La propia aplicación node

## thumbService Servicio que atiende peticiones para reducir el tamaño de imágenes

## API nodepop
Mediante supervisorThe project can be viewed on a development server at localhost:3000 by running:
```
npm start
```


### Resources:

- https://htmlpreview.github.io/?https://github.com/rabelsan/devops/blob/main/apiDoc/index.html
