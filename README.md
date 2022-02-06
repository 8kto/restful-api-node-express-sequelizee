# Simple RESTful API with Node.js, Express, and Sequelize  

The application is written according to this guide:
[Getting Started with Node, Express and Postgres Using Sequelize
](https://www.digitalocean.com/community/tutorials/getting-started-with-node-express-and-postgres-using-sequelize?utm_source=pocket_mylist)

Original repo: https://github.com/waiyaki/postgres-express-node-tutorial

## Install
0. Run `npm install`
1. Create `server/config/config.json` file: 
```json
{
  "development": {
    "username": "postgres",
    "password": "postgres",
    "database": "todos-dev",
    "host": "127.0.0.1",
    "port": 5432,
    "dialect": "postgres"
  },
  "test": {},
  "production": {}
}
```

2. Run `npm run start:dev`
3. Import a Postman collection from [./nodejs-rest-api.postman_collection.json](./nodejs-rest-api.postman_collection.json)