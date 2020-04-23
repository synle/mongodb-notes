# MongoDB Note

### Default Port: 27017

### Setting it up with docker
Docker image URL: https://hub.docker.com/_/mongo
#### Run mongodb
```
docker run --name some-mongo -d mongo:tag
```

#### To start and connect to it with another docker
```
docker run -it --network some-network --rm mongo mongo --host some-mongo test
```

#### Connect to mongo
```
docker exec -it ff32bc4e4b17 bash

mongo
```
