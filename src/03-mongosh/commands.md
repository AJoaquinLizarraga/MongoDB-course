<!-- @format -->

## Connect to container

```sh
docker-compose exec mongodb bash
```

## Connect with mongosh

```sh
mongosh "url de atlas o base de datos de docker"
```

```sh
show dbs

show collections

use("platzi_store")
db.products.find()
```
