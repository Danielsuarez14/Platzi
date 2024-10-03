## Connect to container
```sh
docker-compose exec mongodb bash
```
## Connect with Mongosh

```sh
mongosh ""
```

```sh
show dbs
show collections
```

```sh
use("platzi_store")
db.products.find()
```