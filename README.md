Docker stack running Redis and Redis-commander
```
./stack up
docker run -it redis:latest redis-cli -h 192.168.1.142
```
List service labels:
```
docker service inspect redis_redis | jq '.[0].Spec.TaskTemplate.ContainerSpec.Labels'
```
