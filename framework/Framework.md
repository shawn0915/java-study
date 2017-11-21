# Framework


- Data
  - [Connection Pool](#connectionpool)
  - [ORM](#orm)
- SOA
  - [~~EJB~~](#ejb)
- [~~jBPM~~](#jbpm)
- [Struts](#struts)
- [Spring](#spring)
- [Dubbo](#dubbo)
- [Logging](#logging)
- [Security](#security)
- [Reference](#reference)

## ConnectionPool

1. c3p0
1. [Apache Commons DBCP](http://commons.apache.org/proper/commons-dbcp/)
1. [Tomcat JDBC](https://tomcat.apache.org/tomcat-8.5-doc/jdbc-pool.html)
1. [**Alibaba Druid**](connectionpool/druid/Druid.md)
1. JBoss
1. WebLogic
1. WebSphere
1. [HikariCP](http://mvnrepository.com/artifact/com.zaxxer/HikariCP)

## ORM
**Object Relational Mapping**

1. [RedHat Hibernate](orm/hibernate/Hibernate.md)
1. [~~Apache ibatis~~](http://ibatis.apache.org/)
1. [**MyBatis**](orm/mybatis/MyBatis.md)

## EJB
Enterprise JavaBeans

1. [EJB3](ejb/EJB3.md)

## jBPM
Java Business Process Management

RedHat JBoss jBPM

[jbpm.org](http://www.jbpm.org)

### Struts
View, Controller

1. ~~Struts1~~
1. [Struts2](struts/Struts2.md)

### Spring
Model -- biz -- Spring Framework

1. [Spring Framework](spring/SpringFramework.md)
1. [Spring Boot](spring/SpringBoot.md)

## Dubbo

- [Alibaba/Dubbo](dubbo/Dubbo.md)
- [dangdangdotcom/Dubbox](https://github.com/dangdangdotcom/dubbox)

## Logging

- Slf4j
- [Apache Log4j 2](logging/Log4j2.md)
- [Logback](logging/Logback.md)
- commons-logging
- jdklogging

## Security

- Apache Shiro

## Reference

- [EJB 3 和 Spring 技术体系比较](http://www.51cto.com/specbook/223/46090.htm)


todo -- Framework Integrate
---

- Spring
  - [x] Spring Boot
    - [x] Spring Boot Actuator
  - [x] Spring Framework
  - [ ] Spring Web
  - [ ] Spring MVC
  - [ ] Spring Session
  - [ ] Spring Retry
- Data
  - [x] Druid
  - [ ] Mybatis
  - [ ] MySQL
  - [ ] Oracle
  - [ ] MongoDB
  - [ ] Redis
  - [ ] Solr
  - [ ] ES
- Log
  - [x] slf4j
  - [x] logback
- [ ] Email
- [ ] Freemarker
- JMS
  - ActiveMQ
- Shiro
- ZK/dubbo
- REST/RESTful


todo -- fe
---

- js
- jQuery
- layui
- easyUI
- bootstrap
- node.js
- vue.js
- mock.js


mark
---
- Elastic-Job: 分布式作业调度框架
- Swagger: Api管理框架
- OkHttp3: http调用框架
- jeesite
