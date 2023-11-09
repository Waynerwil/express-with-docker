## Instructions for Dockerfile:

Comando para crear la imagen
docker build -t docker-express .

Comando para correr la imagen
docker run --name=war-express -p 4444:3000 docker-express