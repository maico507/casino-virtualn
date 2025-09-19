# Casino Virtual

Proyecto base de casino virtual con frontend en React y backend en Node/Express.

## Estructura
- frontend/ : React (interfaz de usuario)
- backend/ : Node/Express (API, autenticación, juegos, billetera, analytics)
- backend/migrations/ : SQL para esquema inicial
- backend/mock/ : catálogo mock de juegos

## Cómo levantar
1. Copiar `.env.example` a `.env` en backend y configurar variables.
2. Iniciar backend con docker-compose: `docker-compose up --build`
3. Iniciar frontend: `npm start` en la carpeta frontend
