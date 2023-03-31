# Docker



| Comando | Descripción |
|---------|-------------|
| `docker run` | Crea un nuevo contenedor a partir de una imagen y lo ejecuta. |
| `docker ps` | Muestra una lista de todos los contenedores en ejecución. |
| `docker images` | Muestra una lista de todas las imágenes disponibles en el sistema. |
| `docker build` | Crea una nueva imagen a partir de un archivo Dockerfile. |
| `docker stop` | Detiene un contenedor en ejecución. |
| `docker rm` | Elimina un contenedor existente. |
| `docker rmi` | Elimina una imagen existente. |
| `docker exec` | Ejecuta un comando dentro de un contenedor en ejecución. |
| `docker pull` | Descarga una imagen desde un registro remoto. |
| `docker push` | Sube una imagen local a un registro remoto. |

| Banderas | Descripción |
|----------|-------------|
| `-d` | Ejecuta el contenedor en segundo plano (modo "detached"). |
| `-p` | Mapea un puerto del host al contenedor. |
| `-v` | Mapea un volumen del host al contenedor. |
| `--name` | Asigna un nombre personalizado al contenedor. |
| `--rm` | Elimina automáticamente el contenedor cuando se detiene. |
| `-it` | Habilita la interactividad con el contenedor. |
| `-e` | Establece una variable de entorno en el contenedor. |
| `--link` | Conecta un contenedor con otro contenedor en ejecución. |
