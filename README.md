
## Spring Cloud项目

基础架构建设

1. 系统拆分	“我从单体系统分裂成了 17 个服务”
2. 服务注册	“我是一个新服务，我刚刚加入注册中心”
3. 配置中心	“我不再用 application.yml，因为我学会了动态感知”
4. 服务调用	“我和朋友们靠 Feign 通话，但有时候我被熔断了”
5. 网关	“我是网关，大家都必须经过我！”
6. 服务治理	“我们微服务之间的矛盾，需要一个‘治理者’”
7. 服务降级	“我不想崩，就先假装服务可用”
8. 服务发现	“我一觉醒来，发现自己被 Eureka 下线了…”
9. 配置中心	“我曾经用配置文件，现在我听 Apollo 的话”
10. 重试机制	“我打了三次电话，对方才接——这不是我粘人，是重试机制！”
11. 网格观测	“我能看到每一个服务之间的秘密通话，因为我叫 Istio”
12. 统一认证	“我是登录服务，整个宇宙都得看我脸色登录”

## 🧩 技术故事集锦：用故事讲透复杂系统（加强版）



## SpringCloud架构解析

SpringCloud,Nacos,Gateway,Seta,Sentinal

## ELK统一日志平台原理和实践

ELK, elasticsearch, logstash, filebeat

## Jenkins 自动化部署

一键部署前后端代码

## 分布式原理和协议

分布式原理、Paxos、Raft

## 部署

## 前端

passjava-portal

### 小程序

passjava-miniApp

## 简介

- 采用流行的技术，如 Spring Cloud项目 SpringBoot、MyBatis、Redis、 MySql、 MongoDB、 RabbitMQ、Elasticsearch，采用Docker容器化部署。

## 连载目录

- 五分钟搞懂分布式基础概念
- 快速搭建Linux环境
- 配置虚拟机网络
- 安装Docker
- Docker安装mysql
- Docker安装redis
- 本地开发环境配置
- 配置Git
- 初始化项目和添加微服务
- 知识系统微服务划分图
- 初始化数据库和表
- 搭建管理后台
- 自动生成前后端代码
- 整合MyBatis-Plus实现CRUD
- 生成所有微服务的CRUD代码
- Spring Cloud Alibaba 组件
- SpringCloud整合Alibaba-Nacos注册中心
- SpringCloud整合OpenFeign组件
- SpringCloud整合Alibaba-Nacos配置中心
- SpringCloud整合Gateway网关
- 管理后台-题目类型功能
- SpringCloud整合OSS对象存储
- 整合统一异常处理
- Elasticsearch（原理）
- Elasticsearch实战
- Elasticsearch集群部署
- 微服务架构中的链路追踪
- 手摸手教你性能压测
- 缓存实战
- 缓存实战-Redis分布式锁
- 缓存实战-Redisson分布式锁
- 缓存实战-SpringCache

## 架构篇

> SpringCloud框架

- Spring Cloud Alibaba 组件
- SpringCloud整合Alibaba-Nacos注册中心
- SpringCloud整合OpenFeign组件
- SpringCloud整合Alibaba-Nacos配置中心
- SpringCloud整合Gateway网关
- SpringCloud整合OSS对象存储
- Spring Cloud整合统一异常处理
- Spring Cloud-Elasticsearch（原理）
- Spring Cloud-Elasticsearch实战
- Spring Cloud-Elasticsearch集群部署
- Spring Cloud微服务架构中的链路追踪
- Spring Cloud手摸手教你性能压测
- Spring Cloud缓存实战
- Spring Cloud缓存实战-Redis分布式锁
- Spring Cloud缓存实战-Redisson分布式锁
- Spring Cloud缓存实战-SpringCache

## Java并发多线程

- 再也不怕被问volatile
- 再也不会被问CAS了
- 用积木讲解ABA原理
- 带你领略集合的线程不安全
- 彻底理解Java中的21种锁
- 庖丁解牛18种Queue，你知道几种？

## 分布式

- 分布式基础概念
- 分布式中的十种坑
- 用三国杀讲分布式算法，舒适了吧？
- 用太极拳讲分布式理论，舒服！
- 诸葛VS庞统，拿下Paxos
- 用动图讲解分布式Raft
- 韩信大招：一致性哈希
- Gossip协议
- QuorumNWR算法
- 区块链12问和Pow算法
- Zookeeper中的ZAB协议

## 架构设计

- 微服务架构中的两款流量防卫兵
- 浅析扣减库存的方案设计
- 订单系统中的补偿事务设计
- 请警惕Elasticsearch的三大坑
- B站崩了，聊聊高可用和异地多活
- 查漏补缺，DDD领域驱动设计
- 自研简易版任务调度框架
- 闲鱼架构演进
- 京东白条数据架构演进
- 春晚红包架构
- 淘宝架构10年

## SpringCloud 架构剖析

- 注册中心Eureka
- Eureka基本原理和简单使用
- Eureka本地集群搭建
- Eureka源码之启动过程
- Eureka源码之客户端注册
- Eureka源码之服务端接收注册信息
- Eureka源码之客户端首次获取注册表
- Eureka源码之客户端增量获取注册表
- Eureka源码之Server端的多级缓存机制
- Eureka控制台参数说明
- 负载均衡Ribbon
- Ribbon架构剖析
- 远程调用Feign
- Feign远程调用基本原理和使用
- Feign架构剖析
- 熔断限流Hystrix
- Hystrix架构剖析
- Gateway网关
- Gateway网关基本原理和使用
- Gateway网关架构剖析
- Nacos配置注册中心
- Nacos架构原理①：一条注册请求会经历什么？
- Nacos架构原理②：揭秘AP架构——Distro一致性协议
- Sentinel限流
- 分布式事务
- Hystrix和Sentinel选型对比
- 分布式锁
- 分布式锁架构剖析
- 分布式锁实战
- 分布式锁实战-Redisson
- 分布式锁实战-Redis分布式锁
- 分布式锁实战-分布式锁总结

## 用故事讲解技术

- 中间件选型
- 消息队列
- 链路追踪
- 他们把熔断限流玩到了极致
- 我是一个秒杀请求，正在逃离这颗星球
- 为什么要除夕，原来是内存爆了
- 面试官：你了解分布式锁吗？
- 面试官：你了解分布式事务吗？
- 面试官：你了解分布式ID吗？
- Redis和MySQL如何保证数据一致性？
- 并发编程
- MySQL
- JVM

### 🧱 中间件选型：三国鼎立

- 在技术的战国时代，Kafka、RabbitMQ 和 RocketMQ 各自为政。
- Kafka 是北境之王，处理亿级数据洪流，善于批量吞吐。
- RabbitMQ 是东域智者，强调可靠性，事务性强，适合银行。
- RocketMQ 是中原军神，阿里系本土精英，拥有精细的消息轨迹。
- 项目经理如诸葛亮，需择主明投：高吞吐选 Kafka，事务优先选 RabbitMQ，国产兼容选 RocketMQ。

### 🚀 我是一个秒杀请求，正在逃离这颗星球

- 秒杀请求，我刚刚被用户点击下单触发了
- 我来到了订单服务，被放入消息队列缓冲
- 我穿过了网关的限流器，差点就被丢弃了！
- 然后我穿过了网关的熔断器，如果前方服务宕了，我就直接断路返回了。
- 幸运的是，我成功进入订单服务，被放入消息队列缓冲。
- 最后到达库存服务时，Redis 判断库存还有，数据库快速减库存。
- 我安然穿越亿万请求洪峰，被高并发系统妥善托管！

### 🧯 他们把熔断限流玩到了极致

- 在分布式系统中，熔断限流是保护系统的利器。
- 熔断器就像电路开关，一旦某个服务错误率爆炸，就“啪”一下断开，保护其他服务。
- 限流器像城市地铁的闸机：超过 1000QPS？暂停进入。
- 降级机制也上线了：系统检测响应变慢，自动切换到“轻接口”。

### 🔍 链路追踪：我是 Zipkin，一位侦探

- Zipkin是一位侦探，专门追踪一次请求的全部旅程。
- 从前端 H5 发起请求那一刻，我就在记录。
- 到网关、鉴权服务、用户服务、订单服务、支付服务，我全都打点。
- 最终，我告诉你：“哦！这次请求卡在了订单数据库上——耗时 800ms。”

## Full GC

- Full GC 是大扫除，不仅清理年轻代，还清理老年代。
- Full GC 是大搬家，不仅清理内存，还清理元空间。
- Full GC 是大扫除，不仅清理垃圾，还清理碎片。
- Full GC 是大扫除，不仅清理内存，还清理磁盘。
- Full GC 是大扫除，不仅清理内存，还清理缓存。
- Full GC 是大扫除，不仅清理内存，还清理日志。
- Full GC 是大扫除，不仅清理内存，还清理文件。
- YGC 是小扫除，年轻代清空；
- FGC 是大搬家，老年代也不放过。

## 内存

- 内存溢出和内存泄漏
- JVM内存模型
- JVM内存结构
- JVM垃圾回收
- JVM垃圾回收算法
- JVM垃圾回收器
- JVM调优实战
- JVM调优案例
- JVM调优工具
- JVM参数列表
- JVM参数调优
- JVM参数调优实战
- JVM参数调优案例
- JVM参数调优工具
- JVM参数调优总结

## 设计模式

- 观察者模式ObserverPattern
- 备忘录模式MementoPattern
- 原型模式PrototypePattern
- 中介者模式MediatorPattern

## 问题

- 删除binlog问题
- 导出报表问题
- List和ArrayList如何选择

## 分享

- Nginx Location 正则

## JVM

- 让你懂JVM
- JVM的三大参数类型
- 字节码指令表
- JVM参数列表

### 💬 面试官：你了解分布式锁吗？

- “我开了一家电影院，只有一个座位。”
- Redis 锁就像前台卖票小妹，用 `SETNX` 先来先得。
- RedLock 是链锁，各家影院都确认座位后才出票。
- ZooKeeper 锁更严谨：排队机制，谁排头谁得锁。

### 📦 分布式事务：老大娘过马路

- 有三个儿子（订单、库存、支付）必须一起行动：
- 使用 TCC 模式就像先拉绳子（Try），确定能走（Confirm）或退回原地（Cancel）。
- MQ 事务消息则是：给每人发纸条，等大家都签收再真正提交。
- 他们要么一起成功，要么一起失败，这就是分布式事务的精髓。

### 🧾 分布式ID：一张身份证的诞生

- “我是一个 ID，我要全球唯一！”
- Snowflake 用时间戳 + 机器 ID + 自增序列组成，像身份证号码一样。
- UUID 就是随便取个全球唯一的名字，太长了不好读。
- 在高并发系统中，没有我，数据就乱套。


### 🧠 Redis + MySQL 一致性：双写之间的博弈

- 用户刚下单，系统同步写入 Redis 和 MySQL。
- 如果写 Redis 成功、MySQL 失败，就数据不一致。
- 所以引入消息队列补偿机制，或者采用延迟双删策略。
- 数据一致性，就是让两个世界的数据最终和谐如初。

### 🔄 并发编程：我是线程，我要争资源！

- 多线程像是多个熊孩子抢一个玩具。
- synchronized 像父母在场，谁也不许乱抢。
- ReentrantLock 提供更多控制，比如超时、公平性。
- volatile 保证变量的可见性，但没法控制“谁先拿”。

### 🧮 MySQL：一段数据的自我修养

- “我是一个表中的数据，我怕三件事：慢查询、锁表、脏数据。”
- B+Tree 帮我快速被找到。
- InnoDB 事务日志保护我免于突然断电。
- 索引过多我会累，锁争抢我会死。

### 🔥 JVM：我是你运行时的灵魂

- 我是 JVM，我掌管你所有的 Java 程序生命。
- ClassLoader 是我招兵买马的官。
- GC 是我扫地的仆人。
- 内存区域：堆、栈、方法区，都是我的领地。
- 优化 JVM，就像调兵遣将，必须知其人、用其能。

## 业务篇

## SpringBoot

- SpringBoot整合Jdbc
- SpringBoot整合Druid
- SpringBoot整合Mybatis
- SpringBoot Mybatis逻辑删除
- Object划分
- SpringBoot缓存实战
- SpringBoot缓存实战-Redis分布式锁
- SpringBoot缓存实战-Redisson分布式锁
- SpringBoot缓存实战-SpringCache
- SpringBoot整合Elasticsearch
- SpringBoot整合Elasticsearch实战
- SpringBoot整合Elasticsearch实战-商品搜索
- SpringBoot整合Elasticsearch实战-商品搜索-自动补全
- SpringBoot整合Elasticsearch实战-商品搜索-过滤和排序
- SpringBoot整合Elasticsearch实战-商品搜索-分页和聚合
- SpringBoot整合Elasticsearch实战-商品搜索-高亮
- SpringBoot整合Elasticsearch实战-商品搜索-ik分词器
- SpringBoot整合Elasticsearch实战-商品搜索-拼音分词器
- SpringBoot整合Elasticsearch实战-商品搜索-自定义分词器
- SpringBoot整合Elasticsearch实战-商品搜索-自定义分词器-中文
- SpringBoot整合Elasticsearch实战-商品搜索-自定义分词器-英文
- SpringBoot整合Elasticsearch实战-商品搜索-自定义分词器-英文-词性
- SpringBoot整合Elasticsearch实战-商品搜索-自定义分词器-英文-词性-停用词
- SpringBoot整合Elasticsearch实战-商品搜索-自定义分词器-英文-词性-停用词-同义词
- SpringBoot整合Elasticsearch实战-商品搜索-自定义分词器-英文-词性-停用词-同义词-自定义词库
- SpringBoot整合Elasticsearch实战-商品搜索-自定义分词器-英文-词性-停用词-同义词-自定义词库-自定义词库-加载

## 部署篇

- 快速搭建Linux环境-运维必备
- 配置虚拟机网络
- 安装Docker
- Docker安装mysql
- Docker安装redis
- 本地开发环境配置
- 配置Git

## 💪🏻擅长微服务、分布式、架构设计。



