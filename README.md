# Proyecto MERN

Este es un proyecto desarrollado con el stack **MERN** (MongoDB, Express.js, React, Node.js).

## 📑 Tabla de Contenido

1. [Descripción](#-descripción)
2. [Características](#-características)
3. [Tecnologías Utilizadas](#-tecnologías-utilizadas)
4. [Requisitos Previos](#-requisitos-previos)
5. [Instalación](#-instalación)
6. [Ejecución del Proyecto](#-ejecución-del-proyecto)
7. [Estructura del Proyecto](#-estructura-del-proyecto)
8. [Scripts Disponibles](#-scripts-disponibles)
9. [Pruebas](#-pruebas)
10. [Contribución](#-contribución)
11. [Licencia](#-licencia)

## 📖 Descripción

Este proyecto MERN tiene como objetivo servir de base para el desarrollo de aplicaciones web modernas, escalables y modulares. Incluye una arquitectura preconfigurada para frontend y backend, además de conexión con base de datos MongoDB.

## ✨ Características

- API REST con Express.js y Node.js.
- Interfaz de usuario con React y React Router.
- Base de datos MongoDB con Mongoose.
- Autenticación con JWT.
- Manejo de variables de entorno con dotenv.
- Pruebas unitarias y de integración.

## 🛠 Tecnologías Utilizadas

- **MongoDB**
- **Express.js**
- **React**
- **Node.js**
- Mongoose
- JWT
- Jest / Mocha (para pruebas)
- Docker (opcional)

## 📋 Requisitos Previos

Antes de comenzar, asegúrate de tener instalados:

- [Node.js](https://nodejs.org/) v16 o superior
- [npm](https://www.npmjs.com/) o [yarn](https://yarnpkg.com/)
- [MongoDB](https://www.mongodb.com/try/download/community)
- [Git](https://git-scm.com/)

## ⚙️ Instalación

Clona este repositorio y entra en la carpeta del proyecto:

```bash
git clone https://github.com/usuario/proyecto-mern.git
cd proyecto-mern
```

Instala las dependencias en el backend y frontend:

```bash
# Backend
cd backend
npm install

# Frontend
cd ../frontend
npm install
```

## 🚀 Ejecución del Proyecto

Ejecutar backend:

```bash
cd backend
npm run dev
```

Ejecutar frontend:

```bash
cd frontend
npm start
```

## 📂 Estructura del Proyecto

```bash
proyecto-mern/
│── backend/        # Servidor Express + API
│   ├── src/
│   ├── tests/
│   └── package.json
│
│── frontend/       # Aplicación React
│   ├── src/
│   ├── public/
│   └── package.json
│
│── .env.example    # Variables de entorno
│── docker-compose.yml (opcional)
│── README.md
```

## 📜 Scripts Disponibles

### Backend

- `npm run dev`: Ejecuta el servidor en modo desarrollo.
- `npm run start`: Ejecuta el servidor en producción.
- `npm run test`: Ejecuta las pruebas.

### Frontend

- `npm start`: Ejecuta la app en modo desarrollo.
- `npm run build`: Genera la versión de producción.
- `npm test`: Ejecuta pruebas.

## 🧪 Pruebas

Para correr pruebas en backend o frontend:

```bash
npm run test
```

## 🤝 Contribución

¡Las contribuciones son bienvenidas!

1. Haz un fork del proyecto.
2. Crea una rama para tu nueva funcionalidad (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza un commit de tus cambios (`git commit -m 'Agrega nueva funcionalidad'`).
4. Haz push a tu rama (`git push origin feature/nueva-funcionalidad`).
5. Crea un Pull Request.

## 📄 Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE para más información.
