# kafka-flink-stack-docker-compose
****
### container structure
- kafka broker : 3
- zookeeper : 1
- kafdrop (Web UI): 1
- flink job manager : 1
- flink task manager : 1
- flink sql client : 1

### quick start
```
1) network 생성
$ docker network create jssvs-net

2) docker-compose up
$ docker-compose -f docker-compose.yml up -d
```


### browser connection
- kafdrop : http://localhost:9000
- filnk dashboard : http://localhost:8081
  