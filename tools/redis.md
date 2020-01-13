[< Back](./../README.md)

# Redis

### Install
```bash
	docker run --name redis -p 6379:6379 -d redis
```

### Connect
```bash
    docker exec -it redis sh
```

Use following command to run `redis-cli` after connecting to server
```bash
    redis-cli
```

### Usage
- [Exploring Redis with Docker](https://markheath.net/post/exploring-redis-with-docker)