## Meteor Postgres Apollo Shopping Cart

## Setup Postgres Mac OSX

1. Get [http://postgresapp.com/](http://postgresapp.com/)

2. Install and run.

3. In the pg console, create and connect to the database
```
CREATE DATABASE shoppingdb;
\c shoppingdb
```
## Setup Database config
1. Copy settings.sample.json to settings.json.

2. Update settings.json for shoppingdb host,
dbtype, dbname, username and password.

*dbtype value can be 'mysql','mariadb','sqlite','postgres' or 'mssql'.

## Install npm packages & start meteor
```js
npm install

npm start
```


## Contribute
It'd be cool to see the feature set expand, and cleaned up. If you want to get involved file issues and
make prs.
