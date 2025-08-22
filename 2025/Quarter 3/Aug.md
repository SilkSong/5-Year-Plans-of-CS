## Week 1

2025.8.1

* MyBatis 的缓存简介, 一级缓存，二级缓存，自定义缓存和缓存原理

2025.8.2

* Spring 简介, IOC 本质

2025.8.3

* HelloSpring

2025.8.4

* 各种依赖注入方式

2025.8.4

* Linux 命令:
    * 查看内存: top M
    * 模糊匹配文件: ls -l  \*keyword\*
    
## Week 2  

2025.8.12

* Linux 命令:
    * 查看文件大小: `du -sh`; `du -h`
* 使用了 Spring 的注解实现自动装配, 使用了 Configuration 注解来代替 XML
* 介绍了静态代理模式和其理解, 为了解 AOP 打基础

2025.8.13

* 快速看完了 Spring 剩余教程, 包括动态代理, AOP, 整合 Mybatis, 事务等等, 看的比较草率, 感觉用处不大, 希望在 SpringBoot 那里可以完整学习


2025.8.16

* `reader.readLine()` 会读取当前行的内容 (第一行)，并移动指针到下一行的开头(即第二行)
* 开始了 SpringMVC 的学习, 回顾了 MVC 的基本架构, 回顾(了解)了 Servlet 的知识, 对 SpringMVC 的执行原理, 用 `DispatcherServlet` 还有一系列的 `handleMapper` `handlerAdapter` 进行了了解, 然后学习了注解进行 SpringMVC 开发, 注解还是太方便了, 框架帮我们做了太多的事, 然后是 `@RequestParam` `@GetRequest` 等注解的使用

2025.8.17

* 快速看完了 SpringMVC 视频
* 了解了JSON, 了解了JSON解析的三个库: Jackson, FastJSON2, Hutools.JsonUtil
* 学习了 `JUnit` 测试的一些心得, 包括 SpringBoot 框架下主程序入口, @SpringApplication的包扫描原则, 设计到 test 和 其他 Bean 的目录结构等等, Spring 的扫描是基于包名，而不是源代码物理目录
* SQL: `to_date('2025-08-11 13:23:32', 'YYYYY-MM-DD HH24:MI:SS')`
* JAVA: `simpledateFormat("yyyy-MM-dd HH:mm:ss")`

## Week 3

2025.8.22

* 正式开始了 SpringBoot 的学习