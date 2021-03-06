# microservices-zk

This is a distributed tracing based on ZK [V3.5.6](https://blog.csdn.net/xiaobin_HLJ80/article/details/8836252).

## ZK Run
```bash
zkServer.sh start
```
### ZK command line
```bash
zkCli.sh
```
search services:
```bash
ls /services
```

## user service
* user-service [springcloud-zk-user-service](https://github.com/xiaobin80/microservices-zk/tree/master/springcloud-zk-user-service)
* userDetails [springcloud-zk-userDetails](https://github.com/xiaobin80/microservices-zk/tree/master/springcloud-zk-userDetails)

## gate way
* zuul [gateway-zuul](https://github.com/xiaobin80/microservices-zk/tree/master/gateway-zuul)

## Document
* Distributed traceability with Spring Cloud: [Sleuth and Zipkin](https://www.cnblogs.com/xiaobin-hlj80/p/10052026.html)