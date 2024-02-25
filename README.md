docker stack deploy -c redis.yml redis
docker run -it redis:latest redis-cli -h 192.168.1.142
