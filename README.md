# MongoDB Note

### Default Port: 27017

### Setting it up with docker
#### Run mongodb
```
docker run --name some-mongo -d mongo:tag
```

#### To connect to it with another docker
```
docker run -it --network some-network --rm mongo mongo --host some-mongo test
```
