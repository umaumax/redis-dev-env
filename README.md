# redis-dev-env

## how to run
``` bash
docker compose up -d
```

## how to confirm
``` bash
$ redis-cli -h localhost -p 6379
localhost:6379> SET hello_key "Hello Redis!"
OK
localhost:6379> GET hello_key
"Hello Redis!"
```

## how to terminate
```
docker compose down
```
