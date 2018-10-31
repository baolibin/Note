
##### 消息队列

    消息队列Message Queue是一种应用程序与应用程序之间通信的方法。

    常用的消息队列如下：
    ActiveMQ：ActiveMQ 是Apache出品，最流行的，能力强劲的开源消息总线。
    RabbitMQ：AMQP协议的领导实现，支持多种场景
    RocketMQ
    ZeroMQ：史上最快的消息队列系统
    MetaMQ
    Kafka：高吞吐，在一台普通的服务器上既可以达到10W/s的吞吐速率；完全的分布式系统。适合处理海量数据。


* [ActiveMQ官网](http://activemq.apache.org/)
* [Active文档](http://activemq.apache.org/getting-started.html#GettingStarted-MonitoringActiveMQ)

##### 为什么使用MQ
    在高并发环境下，由于来不及同步处理，请求往往会发生堵塞,通过使用消息队列，
    我们可以异步处理请求，从而缓解系统的压力。


    消息中间件利用高效可靠的消息传递机制进行平台无关的数据交流，并基于数据通信来进行分布式系统的集成。
    通过提供消息传递和消息排队模型，它可以在分布式环境下扩展进程间的通信。
    对于消息中间件，常见的角色大致也就有Producer（生产者）、Consumer（消费者）

---
参考：
1.ActiveMQ https://www.e-learn.cn/content/java/487993
