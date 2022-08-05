Boilerplate to setup a [Postgres](https://www.postgresql.org/ "Postgres' Homepage") database with [Prisma](https://www.prisma.io/ "Prisma's Homepage") ORM.

# Run it with docker

```
$ docker-compose up -d
```

## open prisma container

```
$ docker exec -it prisma bash
or
$ docker attach prisma
```

## migrate database

```
$ npm run migrate
```
