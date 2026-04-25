# Leury Brand - Dev Card

Tarjeta personal de desarrollador construida con Node.js y Docker, desplegable como contenedor.

## Tecnologias

- Node.js + Express
- HTML/CSS (vanilla)
- Docker
- GitHub Actions (CI/CD)

## Estructura

    devops-hola-mundo/
    ├── .github/
    │   └── workflows/
    │       └── deploy.yml
    ├── public/
    │   └── index.html
    ├── index.js
    ├── package.json
    ├── Dockerfile
    └── .dockerignore

## Correr localmente

    npm install
    node index.js

Abre: http://localhost:4000

## Correr con Docker

    docker build -t lb19/practica-continua:latest .
    docker run -p 4000:4000 lb19/practica-continua:latest

## Imagen en Docker Hub

    docker pull lb19/practica-continua:latest

Repositorio Docker Hub: https://hub.docker.com/r/lb19/practica-continua

## App en produccion

https://practica-devops-latest.onrender.com

## Repositorio

https://github.com/lb19082004/practica-continua
