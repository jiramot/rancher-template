#Redis cluster

## Purpose
Run a Redis cluster [see sample](http://rancher.com/guest-blog-building-a-redis-cluster-with-docker-and-rancher-on-digital-ocean/)

### How to use
```
cd src
./redis-trib.rb create --replicas 1 10.42.251.230:7000 10.42.27.151:7000 10.42.27.160:7000 10.42.138.181:7000 10.42.11.78:7000 10.42.151.100:7000
```
