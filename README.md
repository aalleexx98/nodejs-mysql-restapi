# Nodejs MYSQL REST API

### Installation

```
cd nodejs-mysql-restapi
docker-compose up
npm install
npm run dev
```

1. Creamos carpeta
2. Abrimos terminal y comando npm init -y
3. npm i express para añadir express.
4. En el package.json debajo de main añadimos   "type": "module", para poder utilizar los import ... from ...
5. npm i nodemon -D para tener hot reloading o como se llame. (Esto solo para desarrollo en producción no se recomienda tenerla activa).
6. En scripts añadimos la linea de (nodemon):
 "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "dev": "nodemon index.js"
  },
 y ya podremos ejecutar la app con npm run dev




--------------------------------------------------------------------------
7. Nos conectamos a mysql y creamos databases sudo mysql -u root -p
8. npm i mysql2, modulo para conectarse a la base de datos.
