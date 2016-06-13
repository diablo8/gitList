# soa中间件

#1. [motan](https://github.com/weibocom/motan)
   微博的 RPC 框架 Motan 属于服务治理类型，是一个基于 Java 开发的高性能的轻量级 RPC 框架，Motan 提供了实用的服务治理功能和优秀的 RPC 协议扩展能力。
  
Motan 提供的主要功能包括：
```
服务发现 ：服务发布、订阅、通知
高可用策略 ：失败重试（Failover）、快速失败（Failfast）、异常隔离（Server 连续失败超过指定次数置为不可用，然后定期进行心跳探测）
负载均衡 ：支持低并发优先、一致性 Hash、随机请求、轮询等
扩展性 ：支持 SPI 扩展（service provider interface）
其他 ：调用统计、访问日志等
```

#2. [dubbo](https://github.com/alibaba/dubbo)
   DUBBO是一个分布式服务框架，致力于提供高性能和透明化的RPC远程服务调用方案，是阿里巴巴SOA服务化治理方案的核心框架

#3. [dubbox](https://github.com/dangdangdotcom/dubbox)
   Dubbo eXtension。当当网开源项目，可为Dubbo服务框架提供多项扩展功能，包括REST风格远程调用、Kryo/FST序列化等等。

#4. [dubbox-demos](https://github.com/shuvigoss/dubbox-demos)
   基于dubbox使用手册。