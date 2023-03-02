<brigos.com.br>

$ yarn init -y

$ yarn add typescript ts-node-dev @types/express -D

$ yarn add express typeorm reflect-metadata mariadb

$ mkdir src

$ touch src/server.ts

$ echo "import express from 'express';

const app = express();

app.get('/', (req, res) => {
    return res.send('Hello World!');
});

app.listen(3000, () => console.log('Servidor está rodando'));" > src/server.ts

$ yarn tsc --init

(tsconfig.json)
>"target": "es2021", 
>"experimentalDecorators": true,
>"emitDecoratorMetadata": true,

$ sudo mysql -u root
$ CREATE USER 'admin'@localhost IDENTIFIED BY 'admin';
$ CREATE DATABASE 'code_drops_crud';
$ GRANT ALL PRIVILEGES ON code_drops_crud.* TO admin@localhost;
$ FLUSH PRIVILEGES;
$ SHOW GRANTS FOR admin@localhost;
