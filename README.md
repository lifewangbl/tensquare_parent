# 社交系统
#### 项目介绍
      《社交系统》采用目前主流的微服务系统架构SpringBoot+SpringCloud+SpringData进行开发，前端技术采用Vue.js。系统整体分为三大部分：微服务、网站前台、网站管理后台。功能模块包括文章、问答、招聘、活动、吐槽、交友、用户中心、搜索中心及第三方登录等。
      本项目融合了Docker容器化部署、第三方登录、SpringBoot、SpringCloud、SpringData、人工智能、爬虫、RabbitMQ等技术。
#### 开发环境、开发工具
      1、JDK1.8
      2、idea2019
      3、git
      4、Navicat Premium
#### SpringData查询和分页
      1、利用Specification接口实现复杂查询。
      2、Pageable实现分页。
      3、常用查询方法：in、join、equal等。
      4、优点：不需要写映射，少写方法和对应字段。
      5、缺点：SpringData主张表和对象的关系映射，但实际业务错综复杂，需要编写复杂的SQL解决，这方面没有mybatis好用。
      6、SpringDataJPA命名规则生成SQL语句。
      