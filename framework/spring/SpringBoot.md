# Spring Boot
v1.5.8


- Spring
  - [SpringBootActuator](#actuator)
  - [SpringFramework](SpringFramework.md)
    - [spring-core](SpringFramework.md#core)
- Integration
  - [Druid](../connectionpool/druid/Druid.md)
  - [MyBatis](../orm/mybatis/MyBatis.md)
- [banner](http://www.patorjk.com/software/taag/)

## Command

- run
```bash
mvn spring-boot:run
java -jar target/spring-boot-demo.jar
```

## Actuator

url
```
http://localhost:8081/health
http://localhost:8081/info
http://localhost:8081/env
http://localhost:8081/metrics
http://localhost:8081/configprops
```




## REF

- [start.spring.io](https://start.spring.io)
- [spring-boot/reference](https://docs.spring.io/spring-boot/docs/current/reference/html/)
- [spring-boot/reference/using-boot-starter](https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/#using-boot-starter)
- [guides](https://spring.io/guides/gs/spring-boot/)
- [Common application properties](https://docs.spring.io/spring-boot/docs/1.5.8.RELEASE/reference/htmlsingle/#common-application-properties)

### actuator

- [spring/actuator-service](http://spring.io/guides/gs/actuator-service/)
- [spring-boot-actuator](http://javabeat.net/spring-boot-actuator/)