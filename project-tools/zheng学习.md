# zheng 学习

## zheng部署启动
* 查看服务，确认mysql服务、redis服务运行正常；
* 进入E:\ideaProjects\zheng\project-tools目录，依次执行activemq.bat、zkServer.cmd、nginx.bat、tomcat_home.bat；
* 启动idea，打开zheng，运行upms-rpc-server、cms-rpc-server；
* 通过jetty运行upms-server、cms-server。

## zheng-upms学习
* mybatis 动态数据源配置及实现 DynamicDataSource；
* dubbo 服务接口注册spring整合 **applicationContext-dubbo-provider.xml**；
* dubbo 接口调用 及spring整合 **applicationContext-dubbo-consumer.xml**；
* 了解ehcache，配置**ehcache.xml**及spring整合**applicationContext-ehcache.xml**，注解的使用
* 构建web前端的mock server
* 配置文件，开发环境、生产环境 maven profiles
* spring 线程池
* jsp maven freemarker
* jetty tomcat

### idea使用技巧
#### 查找
* 基本查找 Ctrl+F， Ctrl+Shift+F
* 主菜单中选择Navigate | Call Hierarchy命令查看一个Java方法调用树（caller和callee两个方向）
> 快捷键 Ctrl+Alt+H

* 主菜单中选择Analyze | Dataflow from/to Here两个命令查看表达式、变量和方法参数的传递关系树。
* "Find Usage"可以查看一个Java类、方法或变量的直接使用情况。
>  快捷键 Alt+F7

* 查看类关系图 在包或类上右键点击Diagram或者用快捷键Ctrl+Alt+U。
> 快捷键Ctrl+Alt+U

#### 配置tomcat
#### 配置maven-jetty
