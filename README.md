# Authentication API 

This is an authentication API using:

1. Adonis
2. GraphQL
3. MySql

## Setup

Run `npm install`  and  `npm install -g @adonis/cli`


### Database

To run a local mysql database using docker run

```
docker-compose up -d
```

### Migrations

Run the following command to run startup migrations.

```js
adonis migration:run
```

## Development

Run `adonis serve --dev`
