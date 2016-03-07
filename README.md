## 项目说明
```
主要用来扩展zabbix的功能。
```

## 功能说明
```
zabbix自带的功能，主要集中在对OS层面的监控，例如CPU，内存，磁盘空间，网络IO等。
一个业务，虽说运行在OS之上，但总会使用到类似mysql,redis,memcached,mongodb,rabbitmq等中间件。
OS没有发生故障，并不代表业务可用，而业务不可用，往往跟中间件相关。为此才做了这部分扩展，相对来说这部分扩展，离业务更近。
```

## 目录结构说明
```
每一个目录都代表对某个中间件进行监控，目录下面有对应的zabbix模板及相关说明
```