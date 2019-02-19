# 分布式缓存-Redis



Redis是一个开源的、高性能的、基于键值对的缓存与存储系统，通过提供多种键值数据类型来适应不同场景下的缓存与存储需求; 



#### 课程大纲

- Redis数据结构及命令介绍和使用
- Redis实现简易的分布式锁
- Redis中Lua脚本的运用
- Redis持久化AOF/RDB
- Redis集群
- 关于缓存击穿的思考及解决方案



#### 课前准备

>  下载redis的安装包 http://download.redis.io/releases/redis-3.2.11.tar.gz



#### 第一节课

> 主要知识点：redis安装、redis的五种数据结构及常用命令(字符串类型、hash类型、集合类型、有序集合类型、列表类型)、key的设计技巧、redis的事务处理机制、redis发布订阅模式、redis客户端jedis的使用及实践

#### 第二节课

> Lua语言介绍、Lua的基本语法、在Lua脚本中调用redis命令、脚本的原子性分析

#### 第三节课

> Redis的持久化机制(RDB/AOF)、集群部署（复制、哨兵、集群）、关于缓存击穿的常用解决方案

