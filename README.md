# react-around-api-full
The API of "Around the U.S." with authorization and registration handled by the back-end server.

This repository contains the full API of "Around the U.S." project that features user authorization and user registration and handles cards and users.

## Tecnologías utilizadas
-Node.js: Plataforma de ejecución de código JavaScript en el servidor.
-Express.js: Framework web para crear aplicaciones Node.js.
-MongoDB: Base de datos NoSQL utilizada para almacenar los datos de usuarios y tarjetas.
-Mongoose: Biblioteca de modelado de objetos de MongoDB.
-ESLint: Herramienta para mantener un código JavaScript limpio y consistente.
-Nodemon: Utilidad para reiniciar automáticamente el servidor cuando se detectan cambios en los archivos durante el desarrollo.

## Estructura de directorios 
/models: Contiene dos esquemas que definen la estructura de datos para las tarjetas y los usuarios en la base de datos.
/controllers: Define varios controladores que gestionan operaciones para los usuarios y las tarjetas.
/routes: Define las rutas de la API y las vincula con los controladores correspondientes para la gestión de usuarios y tarjetas. 

## Running the Project  
Para ejecutar el proyecto localmente, sigue los siguientes pasos:

1- Clonar el repositorio: 
```bash
git clone https://github.com/Shayenka/react-around-api-full_es.git

2- Instalar las dependencias en el raíz del proyecto:
```bash
npm install

3- Crear el archivo .env y agregar las siguientes variables de entorno:
## variables de entorno
SECRET_KEY=mysecretkey
PORT=3000
MONGODB_URL=mongodb://127.0.0.1:27017/aroundb
NODE_ENV=production
  
`npm run start` — to launch the server.  
  
`npm run dev` — to launch the server with the hot reload feature.  

El servidor se ejecutará en el puerto 3000 por defecto. Puedes acceder a la API a través de http://localhost:3000.

## Dominios del servidor

api.shayenkalvarado.com 
shayenkalvarado.com 
www.shayenkalvarado.com
