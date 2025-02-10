# Desafío: Servidor SoftJobs
Un servidor creado con Node.js, Express y PostgreSQL que gestiona la autenticación de usuarios y las funciones esenciales de la aplicación SoftJobs.
##Descripción
Este proyecto consiste en un servidor backend que ofrece una API RESTful para la gestión de usuarios.

-Permite el registro de nuevos usuarios.
-Facilita el inicio de sesión utilizando JWT.
-Incluye rutas protegidas que requieren autenticación.
-Está diseñado para trabajar con una base de datos PostgreSQL.


1. Inicia el servidor:

- El servidor estará disponible en `http://localhost:3001`, también se modifico en el front para que se comunicaran.

2. Endpoints disponibles:
    - POST /usuarios**: Registramos un nuevo usuario.
    - POST /login**: inicia la sesión y se genera un token JWT.
    - GET /usuarios**: se obtiene los datos del usuario autenticado (requiere token).

3. Tecnologías usadas:

    - Node.js**: Framework de JavaScript para construir el servidor.
    - Express.js**: Para manejar rutas y middlewares.
    - PostgreSQL**: Base de datos relacional.
    - bcryptjs**: Para encriptar contraseñas.
    - jsonwebtoken**: Para la autenticación basada en tokens.
    - dotenv**: Manejo de variables de entorno.



Nota: El archivo .env no se ha añadido al archivo .gitignore con el fin de permitir la visualización de las variables de entorno utilizadas en este proyecto.

## observaciones

se debe levantar los dos carpetas separadas tanto para el backend y el frontend y aplicar npm i a cada uno de las carpetas para cargar el node_modules
# desafio07-SoftJobs
