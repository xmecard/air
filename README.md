# 问题

目前在开发前端的过程中，遇到如下的问题：

+ 1、没有统一的开发标准
+ 2、技术栈无法实现统一
+ 3、没有统一的前端库
+ 4、没有统一的前端ui标准
+ 5、app、微信、h5、小程序必须多端适配，工作量巨大
+ 6、集成困难
+ 7、无法做自动回归测试，人工测试工作量很大
+ 8、等等。。。再补充

如何解决这些问题成为了当前的燃眉之急，需要大家的努力


# 前端阶段性解决方案

目前在app 3.0的工作推进中，暴露出的一些问题，希望在不久的将来可以逐一解决。
主要从以下这几个角度出发：

+ 1、代码格式标准化，使用同一份代码标准
+ 2、技术栈统一，如：都使用react作为标准，vue作为补充
+ 3、建立ui库，选择比较好、社区支撑比较多的第三方
+ 4、建立app、微信、h5、小程序之间的标准，尽量做到一套代码多端适配
+ 5、建立自己的组件库，将一些优秀第三方组件封装成适配内部、适合团队的组件
+ 6、建立标准的发布、集成方法，可以考虑CycleCI等服务
+ 7、建立一套测试机制，做到测试能一部分自动化


# 本框架要实现的内容

既然是一个轻量级的框架，就不应该是一个大而全的系统：

+ 集成网络访问，与目前的api接口系统配套，基础库使用axios，配套工具：api调用生成工具，api前端自动化测试工具
+ 集成常用ui，配套工具：演示代码齐全，api文档完善
+ 集成常用util，将之前的项目做个总结，提取公共模块 ，配套工具： api文档完善
+ 项目初始化脚手架，集成代码标准配置
+ 登录
+ 
