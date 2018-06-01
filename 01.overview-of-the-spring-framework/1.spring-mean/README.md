# 1. Spring 对我们意味着什么

“Spring”这个术语在不同的上下文中意味着不同的事物。它可以用来引用 Spring 框架项目本身，这是它最开始的意义。随着时间的推移，其他 Spring 项目都是在Spring框架之上构建的。大多数情况下，当人们说 Spring 的时候，他们指的是整个 Spring 家族。本参考文档着重于基础：Spring 框架本身。

Spring 框架被划分为不同模块。应用程序可以选择它们需要的模块。Spring 的核心是核心容器的模块，包括一个配置模型和一个依赖注入机制。除此之外，Spring 框架为不同的应用程序架构提供了基础支持，包括消息传递、事务性数据和持久化，以及 web 服务。它还包括基于 Servlet 的 Spring MVC  web 框架，以及 Spring WebFlux reactive web框架。

关于模块的说明：Spring 的框架 jar 包允许被部署到 JDK 9 的模块路径下（“Jigsaw”）。为了在支持 “Jigsaw” 的应用程序中使用，Spring5 框架 的 jar 包带有自动模块名称（“Automatic-Module-Name”）清单条目，它定义了稳定的语言级模块名称（“spring.core”，“spring.context”等），这类模块名称不同于 jar 包的 artifact 名称（jar 包遵循相同的命名模式，使用“-”替代“.”，例如“spring-core”，“spring-context”等）。因此，Spring 的框架 jar 包在 JDK 8 和 9 的类路径上都能保持良好的工作状态。
*（此处本人对 Java 8+的特性不甚了解，欢迎勘误）*

