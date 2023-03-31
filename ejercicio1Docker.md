# Ejercicio docker

## 1.- Crea un contenedor con una imagen de Ubuntu. Instala tus paquetes preferidos y crea una imagen llamada MiUbuntu basada en dicho contenedor.

**Descargando imagen**
* docker pull ubuntu
**Creando contenedor de la imagen y accediendo**
* docker run -it --name mi-ubuntu ubuntu /bin/bash
    **Instalando paquetes**
    * apt-get update
    * apt-get install nano curl -y
    **Saliendo de contenedor**
    * exit

**Creando nueva imagen a partir del contendeor ubuntu con los paquetes nuevos instalados**
* docker commit mi-ubuntu miubuntu

## 2.- Crea un Dockerfile para personalizar una imagen de Alpine 

**Archivo Docfile**
* FROM alpine:latest
* RUN apk update && \
    * apk add --no-cache nginx curl
* COPY index.html /usr/share/nginx/html
* EXPOSE 80
* CMD ["nginx", "-g", "daemon off;"]


