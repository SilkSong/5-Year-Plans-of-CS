## Week 1

2025.9.4

* homebrew 安装了 Nginx, 学习了一些 homebrew 的知识，学习了 Nginx 的功能, 常用命令, 配置文件的作用

## Week 2

2025.9.12

* 彻底搞懂了 Java 是值传递还是引用传递, 这个问题本质上是在问求值策略。当引用类型的时候是按共享对象传递，它也是值传递的一种特例。并且搞懂了 String 的特殊行为，String 字符串常量池和堆中创建。

2025.9.13

* 学习了 Docker 常用命令

2025.9.14

* 复习了 Docker 常用命令, 包括容器,镜像，`docker top`, `docker cp`, `docker logs` 等

## Week 3

2025.9.15

* 初步了解了 Druid 数据库连接池, 登录了Druid监控前端
* 学习到了线程池的概念, 一个Java后端服务一般有: Tomcat 线程池, 数据库连接池, MQ消费线程池, @Async 线程池, @Scheduled 线程池等, 初步了解了 Java 调度器
* 复习了 Docker 容器数据卷的操作和 Dockerfile 的编写, 包括容器数据卷的指定目录挂载, 具名匿名挂载，Dockerfile 的基本编写，构建，发布语法

2025.9.17

* 复习了 Docker 网络相关:
    * 学习了 /ect/hosts 文件的作用 
    * 学习了子网, 网关的概念, 学习了在一个子网下, 网络地址, 网关地址, 广播地址的概念, 了解了在一个子网下, 具体有多少个容器可以被分配的计算方式
    * 学习了如何建立一个网络, 在自定义网络下run一个容器, 如何用一个网络连通一个容器

2025.9.18

* 对 Docker Compose 和 Docker Swarm 有了一个基本的认识
* 开始正式学习 SpringBoot


## Week 4

2025.9.24

* 初步了解了什么是 VIP, 什么是 LVS, 学习到了服务器上挂载的 FTP服务器实际上是 VIP, 可以保证高可用和负载均衡
* 看完了 Docker 进阶, 复习了 Docker 知识, 复习了交换机和路由器
* 了解了 Java classpath 的概念
* 巩固了 @Controller 和 @RestController 的区别
* 看完了 SpringBoot 教程的前期准备工作, 开始实操员工管理系统

2025.9.25

* 复习了 Java 基本类型的一些基础: 大小类型之间转换, char 类型的本质
* 了解了 ASCII, Unicode 和 UTF-8 之间的关系
* 了解了 Hikari 和 Druid 数据源, 一个是快, 一个是天然监控
* SpringBoot 看到了整合 SpringSecurity


