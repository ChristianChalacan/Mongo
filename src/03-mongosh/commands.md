## Connect to container

``` sh
docker-compose exec mongodb bash
```

## Connect with mongosh
# Connect to local db
``` sh
mongosh "mongodb://root:root123@localhost:27017/?authMechanism=DEFAULT&tls=false"
```

# Connect to external db
``` sh
mongosh "mongodb+srv://admin:PxLzWcZqTYO0LgeJ@mongodblearn.iq1t9wa.mongodb.net/"
```

``` sh
show dbs
show collections
```

``` sh 
use("sample_training")

db.zips.find({ state: "NY" }).count()
```