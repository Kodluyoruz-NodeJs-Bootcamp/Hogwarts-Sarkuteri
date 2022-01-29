## Installation

- You need to create database in `mysql` with `YOUR_DATABASE_NAME`
- `git clone https://github.com/xeusteerapat/node-typeorm-crud.git`
- `npm install`
- create `ormconfig.json` based on your database

```json
{
  "type": "mysql",
  "host": "localhost",
  "port": 3306,
  "username": "YOUR_USER_NAME",
  "password": "YOUR_PASSWORD",
  "database": "YOUR_DATABASE_NAME",
  "entities": ["src/entity/*.ts"],
  "logging": true,
  "synchronize": true
}
```

- `npm start`
