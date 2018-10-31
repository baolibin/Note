
##### redis
    Redis是一个开源（BSD许可），内存存储的数据结构服务器，可用作数据库，高速缓存和消息队列代理。
    它支持字符串、哈希表、列表、集合、有序集合，位图，hyperloglogs等数据类型。
    内置复制、Lua脚本、LRU收回、事务以及不同级别磁盘持久化功能，同时通过Redis Sentinel提供高可用，通过Redis Cluster提供自动分区。

    Redis 是一个基于内存的高性能key-value数据库
    Redis本质上是一个Key-Value类型的内存数据库，很像memcached，整个数据库统统加载在内存当中进行操作，定期通过异步操作把数据库数据flush到硬盘上进行保存。
---
##### 资料
* [redis官网](https://redis.io/)
* [redis中文网](http://www.redis.net.cn/)



---
    1.redis怎样实现持久化？
        RDB、AOF
    2.Redis相比memcached有哪些优势？
        (1) memcached所有的值均是简单的字符串，redis作为其替代者，支持更为丰富的数据类型
        (2) redis的速度比memcached快很多
        (3) redis可以持久化其数据
    3.Redis支持哪几种数据类型？
        String、List、Set、Sorted Set、hashes
    4.Redis回收使用的是什么算法？
        LRU算法


参考：

1. Redis面试题及答案  https://www.toutiao.com/a6586974190702690819/
2. 2018整理最全的50道Redis面试题  https://www.toutiao.com/a6577916688883253768/
