# 一、概述

Spring Boot是由Pivotal团队提供的一套开源框架，可以简化spring应用的创建及部署。它通过自动配置功能，降低了复杂性，同时支持基于JVM的多种开源框架，可以缩短开发时间，使开发更加简单和高效。

该模板使用了Spring Boot框架并集成了mvnw（Maven Wrapper），启动成功后将展示欢迎页。

**预装环境：**`java 17.0.5` `Apache Maven 3.9.1` `Gradle` `git` 等。

注：maven setting mirrors 默认配置了 `腾讯云`。

## 二、快速开始

使用如下编译命令，快速运行此Spring Boot程序：

```
// 使用预装环境 Maven
mvn spring-boot:run
// 为该项目自定义指定 Maven 版本
./mvnw spring-boot:run
```

mvnw: `mvnw`是 Maven Wrapper 的脚本，它的设计目的是减少对本地 Maven 安装的依赖。即使系统中没有安装 Maven，只要项目中包含 `mvnw` 及其相关文件，就可以通过它来运行 Maven 命令。`mvnw` 会根据项目配置自动下载合适版本的 Maven 并使用。

**运行结果：**

<img title="" src="img/output.png" alt="" width="357">

### 三.  文件结构

```
workspace/
├── .mvn
├── .vscode 
│   └── preview.yml   // Cloud Studio 配置文件（运行、预览等）
├── src               
│  └── main
│     └── java
│         └── net/coding/demo
│             └── DemoApplication.java   // 启动入口文件 
│         └── resource
│             └── templates/index.html   // 前端页面
│             └── application.properties // 配置文件
│  └── test/java/net/coding/demo  
│       └── DemoApplicationTests.java   // 测试程序
├── static            // 静态文件存放目录
├── mvnw              // Maven Wrapper 脚本 linux
├── mvnw.cmd          // Maven Wrapper 脚本 windows
├── pom.xml           // maven配置文件，指定依赖版本
├── README.md         // 项目说明文档
├── img               // readme图片目录
|   └── ...                
```

### 2. Spring Boot 官方文档与资源

[Spring Boot 中文文档](https://springdoc.cn/spring-boot/)

[Java Documentation](https://docs.oracle.com/en/java/javase/21/docs/)

[Maven - The Apache Maven Project](https://maven.org.cn/)

[Apache Maven Wrapper &#x2013; Maven Wrapper](https://maven.apache.org/wrapper/)

[mvnrepository](https://mvnrepository.com/)

[gradle](https://gradle.org/)

## 三、  常见问题

[Cloud Studio（云端 IDE） 常见问题-文档中心-腾讯云](https://cloud.tencent.com/document/product/1039/33505)

[Cloud Studio（云端 IDE） | Cloud Studio](https://ide.cloud.tencent.com/docs/)

[Cloud Studio 轻量版 帮助文档](https://docs.qq.com/aio/DRUFZcHVvZlJuY3l2?p=1QOiTiIR9g0KMJneBDyfgM)

## 帮助和支持

##### 欢迎加入Cloud Studio用户反馈群

当您遇到问题需要处理时，您可以直接通过到扫码进入Cloud Studio用户群进行提问.

- 腾讯云工程师实时群内答疑

- 扫码入群可先享受产品上新功能

- 更多精彩活动群内优享

<img title="" src="img/qr-code.png" alt="qr-code.png" width="270">



git config --global user.name "libaohome"
git config --global user.email "libaohome@163.com"
<!-- git remote add origin https://github.com/libaohome/fn-loan-web.git -->
git remote set-url origin https://libaohome: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@github.com/libaohome/fn-loan-service.git
git remote -v

git add .
git commit -m "Initial commit"
git branch -M main
git push -u origin main
https://github.com/libaohome/