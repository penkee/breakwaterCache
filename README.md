# breakwaterCache
支持分布式一致性的本地缓存工具

1、支持本地和远程

2、本地也能一致性，mq方式，rocketmq

3、注解方式，简单

4、无值情况下，缓存时间单独配置，防止雪崩
5、支持单个缓存，list，page，set

6、支持堆外内存
7、支持定时刷新
8、支持spring-boot方式
9、监控统计
10、支持各种缓存开源接入，redis ,pika
11、支持多查询,multiget，多查询也能缓存起来
12、异步加载方式，如果当前过期了，多个请求过来。仍然返回旧的数据，只有一个请求新的，其中同步或者异步都行
