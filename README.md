# SpringBoot-study-doc
———有关SpringBoot的学习文档
### Spring Boot是什么
Takes an opinionated view of building production-ready Spring applications. Spring Boot favors convention over configuration and is designed to get you up and running as quickly as possible.
----- 摘自官网
>>译：Spring Boot遵从约定优于配置，旨在让您尽快启动和运行。
### Spring Boot的特点
* 化繁为简，简化配置
* 备受关注，是下一代Java Web框架
* 微服务的入门级微框架

### Spring Boot 与 Spring的区别
* Spring Boot可以建立独立的Spring应用程序
* Spring Boot内嵌了如Tomcat这样的容器，可以直接运行，无需部署
* Spring Boot无需再像Spring配置繁琐的xml文件；
* Spring Boot将原有的XML配置改为Java配置，将bean注入改为使用注解注入的方式(@Autowire)，并将多个xml、properties配置放在一个appliaction.yml配置文件中
* Spring Boot提供了一些现有的功能，如表单数据验证
* 整合常用依赖，例如spring-webmvc、jackson-json、validation-api等，提供的POM可以简化Maven的配置。当引入核心依赖时，Spring Boot会自引入其他依赖

