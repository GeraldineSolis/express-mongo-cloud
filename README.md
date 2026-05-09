# Express Mongo Cloud - API con JWT

Este proyecto consiste en el desarrollo y despliegue de una API REST utilizando Express y MongoDB Atlas, configurada con un flujo de CI/CD para despliegue automático.

## Requisitos Previos
- Node.js instalado
- Cuenta en MongoDB Atlas 
- Cuenta en Render para el despliegue

## Configuración
1. Clonar el repositorio.
2. Instalar dependencias:
   ```bash
   npm install
3. Configurar las variables de entorno en un archivo .env:
    ````
    PORT=3000
    MONGO_URI=tu_cadena_de_conexion_mongodb
    ````

## Scripts
- npm run dev: Inicia el servidor en modo desarrollo con nodemon.  

- npm start: Inicia el servidor en producción.  

## CI/CD
El proyecto incluye un workflow de GitHub Actions para el despliegue automático en Render al realizar un push a la rama main.  
