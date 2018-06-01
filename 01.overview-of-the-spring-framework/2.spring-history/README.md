# 2. Spring 以及 Spring 框架历史

Spring 在 2003 年成为对早期 J2EE 规范的复杂性的回应。虽然有些人认为 Java EE 和 Spring 是竞争的，但 Spring 实际上是对 Java EE 的补充。Spring 编程模型不包含Java EE 平台规范；相反，它集成了从 Java EE 中精心挑选的如下规范：

* Servlet API ([JSR 340](https://jcp.org/en/jsr/detail?id=340))
* WebSocket API ([JSR 356](https://www.jcp.org/en/jsr/detail?id=356))
* Concurrency Utilities ([JSR 236](https://www.jcp.org/en/jsr/detail?id=236))
* JSON Binding API ([JSR 367](https://jcp.org/en/jsr/detail?id=367))
* Bean Validation ([JSR 303](https://jcp.org/en/jsr/detail?id=303))
* JPA ([JSR 338](https://jcp.org/en/jsr/detail?id=338))
* JMS ([JSR 914](https://jcp.org/en/jsr/detail?id=914))
* 如果需要的话，还可以使用 JTA/JCA 设置来进行事务协调

Spring 框架还支持依赖注入（[JSR 330](https://www.jcp.org/en/jsr/detail?id=330)）和通用注解（[JSR 250](https://jcp.org/en/jsr/detail?id=250)）规范，应用程序开发人员可以选择使用 Spring 框架提供的 Spring 特定机制。

在 Spring 5.0 框架中，Spring 要求最低Java EE 7（例如 Servlet 3.1+、JPA 2.1+），同时在运行时，会使用 Java EE 8 级别的新API（如Servlet 4.0、JSON绑定API）提供开箱即用的集成。这使得 Spring 完全兼容 Tomcat 8 和 9、WebSphere 9 和 JBoss EAP 7。

随着时间的推移，Java EE 在应用程序开发中的角色已经发生了变化。在 Java EE 和 Spring 的早期，创建的应用程序需要被部署到应用服务器上。现在，在 Spring Boot 的帮助下，应用程序是使用被嵌入的易于修改的 Servlet 容器，采用对运维和云友好的方式创建的。在 Spring 5 框架中，WebFlux 应用程序甚至不直接使用 Servlet API，并且可以在非 Servlet 容器的服务器上运行（比如 Netty）。

随着 Spring 的持续创新和发展。除了 Spring 框架之外，还有诞生了一些其他项目，比如Spring Boot、Spring Security、Spring Data、Spring Cloud、Spring Batch等等。 每个项目都有自己的源代码存储库、问题跟踪器和发布节奏。详情请见  Spring 项目的完整列表（[spring.io/projects](https://spring.io/projects)）。

