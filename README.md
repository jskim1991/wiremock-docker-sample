Run docker compose
```shell
docker compose up
```

Check mappings
```shell
curl localhost:8080/__admin/mappings 
```

Send a request (Success case)
```shell
curl -v localhost:8080/api/v1/todos
```

Send a request (Failure case)
```shell
curl -v localhost:8080/api/v1/todos/d8b25784-c16f-449a-9006-6972e8a9111b
```