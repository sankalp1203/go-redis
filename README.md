go-redis is a Redis-like in-memory key-value Database which is multithreaded unlike Redis.

## Table of Contents
* [Commands](#commands)
* [Setup](#setup)
* [Usage](#usage)

### Commands
go-redis supports the following commands as of now:
```
PING, SET, GET, SETNX, MSET, MGET, INCR, DECR, RPUSH, LPUSH, RPOP, LPOP, LRANGE, DEL, EXPIRE, TTL
```

### Setup
To set up go-redis:
1. Clone the repository:  
```
  git clone https://github.com/sankalp1203/go-redis.git
```
2. Run the server
```
  go run .
```

### Usage
1. redis-cli can be used as a client as go-redis also uses the Redis Serialization protocol (RESP).
2. go-redis runs on port 6369 (Redis runs on 6379)
3. Use this command to connect to go-redis
```
redis-cli -p 6369
```
4. Now you are all set to talk to the go-redis server. Try "PING" command to start with and you should receive a "PONG" as response!
