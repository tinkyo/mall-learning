* 序章
  * [mall架构及功能概览](foreword/mall_foreword_01.md)
  * [mall学习所需知识点](foreword/mall_foreword_02.md)

* 架构篇
  * [mall整合SpringBoot+MyBatis搭建基本骨架](architect/mall_arch_01.md)
  * [mall整合Swagger-UI实现在线API文档](architect/mall_arch_02.md)
  * [mall整合Redis实现缓存功能](architect/mall_arch_03.md)
  * [mall整合SpringSecurity和JWT实现认证和授权（一）](architect/mall_arch_04.md)
  * [mall整合SpringSecurity和JWT实现认证和授权（二）](architect/mall_arch_05.md)
  * [mall整合SpringTask实现定时任务](architect/mall_arch_06.md)
  * [mall整合Elasticsearch实现商品搜索](architect/mall_arch_07.md)
  * [mall整合Mongodb实现文档操作](architect/mall_arch_08.md)
  * [mall整合RabbitMQ实现延迟消息](architect/mall_arch_09.md)
  * [mall整合OSS实现文件上传](architect/mall_arch_10.md)

* 业务篇
  * [mall数据库表结构概览](database/mall_database_overview.md)
  * [商品模块数据库表解析（一）](database/mall_pms_01.md)
  * [商品模块数据库表解析（二）](database/mall_pms_02.md)
  * [订单模块数据库表解析（一）](database/mall_oms_01.md)
  * [订单模块数据库表解析（二）](database/mall_oms_02.md)
  * [订单模块数据库表解析（三）](database/mall_oms_03.md)
  * [营销模块数据库表解析（一）](database/mall_sms_01.md)
  * [营销模块数据库表解析（二）](database/mall_sms_02.md)
  * [营销模块数据库表解析（三）](database/mall_sms_03.md)
  * [权限管理功能设计与优化](database/mall_permission.md)
  * [商品SKU功能设计与优化](technology/product_sku.md)

* 技术要点篇
  * [MyBatis Generator使用过程中踩过的一个坑](technology/mybatis_mapper.md)
  * [SpringBoot应用中使用AOP记录接口访问日志](technology/aop_log.md)
  * [SpringBoot应用整合ELK实现日志收集](technology/mall_tiny_elk.md)
  * [前后端分离项目，如何解决跨域问题](technology/springboot_cors.md)
  * [Java 8都出那么久了，Stream API了解下？](technology/java_stream.md)
  * [仅需四步，整合SpringSecurity+JWT实现登录认证！](technology/springsecurity_use.md)
  * [前后端分离项目，如何优雅实现文件存储！](technology/minio_use.md)
  * [前后端分离项目，引入Spring Cloud Gateway遇到的一个问题！](technology/gateway_cors.md)
  * [手把手教你搞定权限管理，结合Spring Security实现接口的动态权限控制！](technology/permission_back.md)
  * [手把手教你搞定权限管理，结合Vue实现菜单的动态权限控制！](technology/permission_front.md)
  * [SpringBoot中处理校验逻辑的两种方式，真的很机智！](technology/springboot_validator.md)
  * [使用Redis+AOP优化权限管理功能，这波操作贼爽！](technology/redis_permission.md)
  * [Elasticsearch项目实战，商品搜索功能设计与实现！](technology/product_search.md)
  * [RabbitMQ实现延迟消息居然如此简单，整个插件就完事了！](technology/rabbitmq_delay.md)

* 部署篇
  * [mall在Windows环境下的部署](deploy/mall_deploy_windows.md)
  * [mall在Linux环境下的部署（基于Docker容器）](deploy/mall_deploy_docker.md)
  * [mall在Linux环境下的部署（基于Docker Compose）](deploy/mall_deploy_docker_compose.md)
  * [mall在Linux环境下的自动化部署（基于Jenkins）](deploy/mall_deploy_jenkins.md)
  * [mall前端项目的安装与部署](deploy/mall_deploy_web.md)
  * [mall-swarm在Windows环境下的部署](deploy/mall_swarm_deploy_windows.md)
  * [mall-swarm在Linux环境下的部署（基于Docker容器）](deploy/mall_swarm_deploy_docker.md)  
  * [微服务架构下的自动化部署，使用Jenkins来实现！](deploy/mall_swarm_deploy_jenkins.md)  
  * [我常用的自动化部署技巧，贼好用，推荐给大家！](technology/springboot_auto_deploy.md)

* 进阶篇
  * [Spring Cloud 整体架构概览](cloud/springcloud.md)
  * [Spring Cloud Eureka：服务注册与发现](cloud/eureka.md)
  * [Spring Cloud Ribbon：负载均衡的服务调用](cloud/ribbon.md)
  * [Spring Cloud Hystrix：服务容错保护](cloud/hystrix.md)
  * [Hystrix Dashboard：断路器执行监控](cloud/hystrix_dashboard.md)
  * [Spring Cloud OpenFeign：基于Ribbon和Hystrix的声明式服务调用](cloud/feign.md)
  * [Spring Cloud Zuul：API网关服务](cloud/zuul.md) 
  * [Spring Cloud Config：外部集中化配置管理](cloud/config.md)
  * [Spring Cloud Bus：消息总线](cloud/bus.md)
  * [Spring Cloud Sleuth：分布式请求链路跟踪](cloud/sleuth.md)
  * [Spring Cloud Consul：服务治理与配置中心](cloud/consul.md)
  * [Spring Cloud Gateway：新一代API网关服务](cloud/gateway.md)
  * [Spring Boot Admin：微服务应用监控](cloud/admin.md)
  * [Spring Cloud Security：Oauth2使用入门](cloud/oauth2.md)
  * [Spring Cloud Security：Oauth2结合JWT使用](cloud/oauth2_jwt.md)
  * [Spring Cloud Security：Oauth2实现单点登录](cloud/oauth2_sso.md)
  * [Spring Cloud Alibaba：Nacos 作为注册中心和配置中心使用](cloud/nacos.md)
  * [Spring Cloud Alibaba：Sentinel实现熔断与限流](cloud/sentinel.md)
  * [使用Seata彻底解决Spring Cloud中的分布式事务问题](cloud/seata.md)
  
* 参考篇
  * [开发者必备Mysql命令](reference/mysql.md)
  * [开发者必备Linux命令](reference/linux.md)
  * [Linux防火墙Firewall和Iptables的使用](reference/linux_firewall.md)
  * [开发者必备Docker命令](reference/docker.md)
  * [使用Maven插件为SpringBoot应用构建Docker镜像](reference/docker_maven.md)
  * [使用DockerFile为SpringBoot应用构建Docker镜像](reference/docker_file.md)
  * [使用Docker Compose部署SpringBoot应用](reference/docker_compose.md)
  * [Hutool中那些常用的工具类和方法 ](reference/hutool.md)
  * [Nginx的这些妙用，你肯定有不知道的！](reference/nginx.md)
  * [使用Jenkins一键打包部署SpringBoot应用，就是这么6！](reference/jenkins.md)
  * [使用Jenkins一键打包部署前端应用，就是这么6！](reference/jenkins_vue.md)
  * [Github标星19K+Star，10分钟自建对象存储服务！](reference/minio.md)
  * [MySql主从复制，从原理到实践！](reference/mysql_master_slave.md)
  * [你还在代码里做读写分离么，试试这个中间件吧！](reference/gaea.md)
  * [Spring Data Redis 最佳实践！](reference/spring_data_redis.md)
  * [Docker环境下秒建Redis集群，连SpringBoot也整上了！](reference/redis_cluster.md)
  * [Elasticsearch快速入门，掌握这些刚刚好！](reference/elasticsearch_start.md)
  * [MongoDB快速入门，掌握这些刚刚好！](reference/mongodb_start.md)
  * [Github标星34K+Star，这款开源项目助你秒建Git服务！](reference/gogs_start.md)
  * [连RabbitMQ的5种核心消息模式都不懂，也敢说自己会用消息队列！](reference/rabbitmq_start.md)

* 工具篇
  * [IDEA常用设置及推荐插件](reference/idea.md)
  * [Navicat实用功能：数据备份与结构同步](reference/navicat.md)
  * [Postman：API接口调试利器](reference/postman.md)
  * [10分钟搭建自己的Git仓库](reference/gitlab.md)
  * [IDEA中的Git操作，看这一篇就够了！](reference/idea_git.md)
  * [虚拟机安装及使用Linux，看这一篇就够了！](reference/linux_install.md)
  * [推荐一个项目管理工具，落地基于Scrum的敏捷开发！](reference/zentao.md)
  * [IDEA中创建和启动SpringBoot应用的正确姿势](reference/idea_springboot.md)
  * [盘点下我用的顺手的那些工具！](reference/my_tools.md)
  * [我用起来顺手的数据库设计工具，这次推荐给大家！](reference/navicat_designer.md)
  * [我常用的IDEA插件大公开，个个是精品！](reference/idea_plugins.md)
  * [IDEA同款数据库管理工具，提示太全了，用起来贼香！](reference/datagrip_start.md)