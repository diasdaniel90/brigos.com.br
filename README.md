<brigos.com.br>
yarn init -y
yarn add typescript express
yarn add typescript ts-node-dev @types/express -D
yarn tsc --init


yarn add typeorm reflect-metadata mariadb




sudo mysql -u root
CREATE USER 'admin'@localhost IDENTIFIED BY 'admin';
CREATE DATABASE 'code_drops_crud';
GRANT ALL PRIVILEGES ON code_drops_crud.* TO admin@localhost;
FLUSH PRIVILEGES;
SHOW GRANTS FOR admin@localhost;

