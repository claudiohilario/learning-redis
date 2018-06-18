# Study of the Redis
## Redis installation in OS X

```cli
mkdir redis && cd redis
curl -O http://download.redis.io/redis-stable.tar.gz
tar xzvf redis-stable.tar.gz
cd redis-stable
make
make test
sudo make install
```
### Initialize Redis Server
```cli
redis-server
```

### Initialize Redis Client
```cli
redis-cli
```
