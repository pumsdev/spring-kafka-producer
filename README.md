# Java
project run on 8088

## Test send message
```sh
curl localhost:8088/kafka/send
```

# user conduktor for monitoring kafka
```sh
docker compose -f docker-compose-conduktor.yml up -d
docker compose -f docker-compose-conduktor.yml down
```
open browser and go to http://localhost:8080