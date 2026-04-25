# 🚀 Leury Brand — Dev Card

Tarjeta personal de desarrollador construida con **Node.js** y **Docker**, desplegable como contenedor.

## 🛠️ Tecnologías

- Node.js + Express
- HTML/CSS (vanilla)
- Docker

## 📁 Estructura
devops-hola-mundo/
├── public/
│   └── index.html
├── index.js
├── package.json
├── Dockerfile
└── .dockerignore

## ▶️ Correr localmente

```bash
npm install
node index.js
```

Abre: http://localhost:4000

## 🐳 Correr con Docker

```bash
docker build -t leury-brand-card .
docker run -p 4000:4000 leury-brand-card
```

## 📦 Imagen en Docker Hub

```bash
docker pull leurybrand/leury-brand-card
!{image alt}(https://github.com/lb19082004/practica-continua/blob/f400ba89dc560c7b60e3d5c496a2de1744b6f7e6/Captura%20de%20pantalla%202026-04-23%20234847.png) 


