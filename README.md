# Spring Cloud 学习项目搭建
## 组员
- 汪喆昊 516030910460
## 项目内容
- [spring-boot-actuator](./spring-boot-actuator)
- [spring-cloud-eureka-config-client](spring-cloud-eureka-config-client)
- [spring-cloud-eureka-config-server](spring-cloud-eureka-config-server)
### spring-boot-actuator
运行项目后，访问[localhost:9001/actuator/health](http://localhost:9001/actuator/health)和[localhost:9001/actuator/info](http://localhost:9001/actuator/info)查看相关信息。
### spring-cloud-eureka-config-client/server
运行server，访问[localhost:8000](http://localhost:8000/)，查看eureka中心信息，目前尚无服务注册。运行client，访问[localhost:8000](http://localhost:8000/)，可以看到已经有一个服务注册。