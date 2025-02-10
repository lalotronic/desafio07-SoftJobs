# Desafío: Servidor SoftJobs
Un servidor creado con Node.js, Express y PostgreSQL que gestiona la autenticación de usuarios y las funciones esenciales de la aplicación SoftJobs.<br>
##Descripción
Este proyecto consiste en un servidor backend que ofrece una API RESTful para la gestión de usuarios.<br>

-Permite el registro de nuevos usuarios.<br>
-Facilita el inicio de sesión utilizando JWT.<br>
-Incluye rutas protegidas que requieren autenticación.<br>
-Está diseñado para trabajar con una base de datos PostgreSQL.<br>


1. Inicia el servidor:<br>

- El servidor estará disponible en `http://localhost:3001`, también se modifico en el front para que se comunicaran.<br>

2. Endpoints disponibles:<br>
    - POST /usuarios**: Registramos un nuevo usuario.<br>
    - POST /login**: inicia la sesión y se genera un token JWT.<br>
    - GET /usuarios**: se obtiene los datos del usuario autenticado (requiere token).<br>

3. Tecnologías usadas:<br>

    - Node.js**: Framework de JavaScript para construir el servidor.<br>
    - Express.js**: Para manejar rutas y middlewares.<br>
    - PostgreSQL**: Base de datos relacional.<br>
    - bcryptjs**: Para encriptar contraseñas.<br>
    - jsonwebtoken**: Para la autenticación basada en tokens.<br>
    - dotenv**: Manejo de variables de entorno.<br>



Nota: El archivo .env no se ha añadido al archivo .gitignore con el fin de permitir la visualización de las variables de entorno utilizadas en este proyecto.<br>

## observaciones

Se debe levantar los dos carpetas separadas tanto para el backend y el frontend y aplicar npm i a cada uno de las carpetas para cargar el node_modules<br>
# desafio07-SoftJobs
