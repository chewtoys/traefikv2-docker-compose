# Traefikv2
Traefik version 2.3


Clonamos el repositorio y editamos las variables del archivo .env

Asignamos nuestro dominio en la variable MY_DOMAIN=tudominio.com 

Tambien sera necesario encriptar nuestro usuario y contraseña para el dashboard de traefik aca un ejemplo.
https://blog.saiyans.com.ve/administracion-tecnologias/traefik-proxy-docker-con-ssl/#Traefik_como_proxy_de_nuestros_contenedores

Una vez hallamos realizado todos los pasos anteriores procederemos con el deploy

$ touch acme.json && chmod 600 acme.json

$ docker-compose up -d

Done
![alt text](https://i.imgur.com/1bXGpGF.png)
