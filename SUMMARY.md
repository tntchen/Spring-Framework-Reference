# Summary

* [前言](README.md)
* [01.Spring 框架概览](01.overview-of-the-spring-framework/README.md)

-----
* [02.IoC 和 AOP 等核心概念](02.core-concepts-such-as-ioc-and-aop/README.md)
    * [1. IoC 容器](02.core-concepts-such-as-ioc-and-aop/1.the-ioc-container/README.md)
        * [1.1. Spring IoC 容器和 beans 的介绍](02.core-concepts-such-as-ioc-and-aop/1.the-ioc-container/1.1.introduction.md)
        * [1.2. 容器概述](02.core-concepts-such-as-ioc-and-aop/1.the-ioc-container/1.2.container-overview.md)
        * [1.3. Bean 概述](02.core-concepts-such-as-ioc-and-aop/1.the-ioc-container/1.3.bean-overview.md)
        * [1.4. Bean 的依赖关系](02.core-concepts-such-as-ioc-and-aop/1.the-ioc-container/1.4.dependencies.md)
        * [1.5. Bean 的作用域](02.core-concepts-such-as-ioc-and-aop/1.the-ioc-container/1.5.bean-scops.md)
        * [1.6. 定制 bean 的特性](02.core-concepts-such-as-ioc-and-aop/1.the-ioc-container/1.6.customizing-bean.md)
        * [1.7. Bean 定义的继承](02.core-concepts-such-as-ioc-and-aop/1.the-ioc-container/1.7.bean-definition-inheritance.md)
        * [1.8. 容器的拓展](02.core-concepts-such-as-ioc-and-aop/1.the-ioc-container/1.8.container-extension-points.md)
        * [1.9. 基于注解配置](02.core-concepts-such-as-ioc-and-aop/1.the-ioc-container/1.9.annotation-based-container-configuration.md)
        * [1.10. Classpath 扫描和组件管理](02.core-concepts-such-as-ioc-and-aop/1.the-ioc-container/1.10.classpath-scanning-and-managed-components.md)
        * [1.11. 使用 JSR 330 标准注解](02.core-concepts-such-as-ioc-and-aop/1.the-ioc-container/1.11.JSR-330-annotations.md)
        * [1.12 基于 Java 配置](02.core-concepts-such-as-ioc-and-aop/1.the-ioc-container/1.12.java-based-container-configuration.md)
        * [1.13. 环境变量抽象](02.core-concepts-such-as-ioc-and-aop/1.the-ioc-container/1.13.enviroment-abstraction.md)
        * [1.14. 注册一个加载时编织器](02.core-concepts-such-as-ioc-and-aop/1.the-ioc-container/1.14.registering-loadtimeweaver.md)
        * [1.15. ApplicationContext 的额外功能](02.core-concepts-such-as-ioc-and-aop/1.the-ioc-container/1.15.additional-capabilities-applicationcontext.md)
        * [1.16 BeanFactory](02.core-concepts-such-as-ioc-and-aop/1.the-ioc-container/1.16.beanfactory.md)
    * [2. 资源](02.core-concepts-such-as-ioc-and-aop/2.resources/README.md)
        * [2.1. 介绍](02.core-concepts-such-as-ioc-and-aop/2.resources/2.1.introduction.md)
        * [2.2. Resource 接口](02.core-concepts-such-as-ioc-and-aop/2.resources/2.2.resource-interface.md)
        * [2.3. 内置 Resource 实现](02.core-concepts-such-as-ioc-and-aop/2.resources/2.3.built-in-resource-implementations.md)
        * [2.4. ResourceLoader 接口](02.core-concepts-such-as-ioc-and-aop/2.resources/2.4.resourceloader.md)
        * [2.5. ResourceLoaderAware 接口](02.core-concepts-such-as-ioc-and-aop/2.resources/2.5.resourceloaderaware-interface.md)
        * [2.6. 资源依赖](02.core-concepts-such-as-ioc-and-aop/2.resources/2.6.resources-dependencies.md)
        * [2.7. 应用上下文和资源路径](02.core-concepts-such-as-ioc-and-aop/2.resources/2.7.application-contexts-and-resource-paths.md)

-----
* [03.Spring 下的测试](03.testing-spring/README.md)
    * 1. Spring 测试介绍
    * 2. 单元测试
        * 2.1. mock 对象
        * 2.2. 单元测试类
    * 3. 集成测试
        * 3.1. 概述
        * 3.2. 集成测试的目标
        * 3.3. JDBC 测试支持
        * 3.4. 注解
        * 3.5. Spring 测试上下文框架
        * 3.6. Spring MVC 测试框架
        * 3.7. PetClinic应用程序范例
    * 4. 更多资源

-----
* [04.数据访问与事务管理](04.data-access-transaction/README.md)
    * 1. 事务管理
        * 1.1. Spring 框架事务管理介绍
        * 1.2. Spring 框架事务支持模型的优点
        * 1.3. 理解 Spring 框架事务抽象
        * 1.4. 资源与事务同步
        * 1.5. 声明式事务管理
        * 1.6. 编程式事务管理
        * 1.7. 声明式与编程式事务管理的选择
        * 1.8. 事务绑定事件
        * 1.9. 特定于应用服务器的集成
        * 1.10. 常见问题的解决方案
        * 1.11. 更多资源
    * 2. DAO 支持
        * 2.1. 介绍
        * 2.2. 统一的（数据访问）异常层次体系
        * 2.3. 用于配置 DAO 或 Repository 类的注解
    * 3. 使用 JDBC 实现数据访问
        * 3.1. 介绍 Spring JDBC 框架
        * 3.2. 使用 JDBC 核心类控制基础的 JDBC 处理过程和异常处理机制
        * 3.3. 控制数据库连接
        * 3.4. JDBC 批量操作
        * 3.5. 利用 SimpleJdbc 类简化 JDBC 操作
        * 3.6. 像 Java 对象那样操作 JDBC
        * 3.7. 参数和数据处理的常见问题
        * 3.8. 内嵌数据库支持
        * 3.9. 初始化 Datasource
    * 4. ORM 和数据访问
        * 4.1. 介绍 Spring 中的 ORM
        * 4.2. 集成 ORM 的注意事项
        * 4.3. Hibernate
        * 4.4. JPA
    * 5. 使用 O/X(Object/XML) 映射器对 XML 进行编组
        * 5.1. 介绍
        * 5.2. 编组器与反编组器
        * 5.3. Marshaller 与 Unmarshaller 的使用
        * 5.4. 基于 XML 架构的配置
        * 5.5. JAXB
        * 5.6. Castor
        * 5.7. JiBX
        * 5.8. XStream
        
-----
* [05.Web 上的 Servlet 和 Reactive 栈-Servlet](05.servlet/README.md)
    * 1. Spring MVC
        * 1.1. 介绍
        * 1.2. DispatcherServlet
        * 1.3. 注解控制器
        * 1.4. Handler 映射
        * 1.5. 解析视图
        * 1.6. 使用 flash 属性
        * 1.7. 构建 URI
        * 1.8. 使用定位
        * 1.9. 使用主题
        * 1.10. Multipart（文件上传）支持
        * 1.11. 异常处理
        * 1.12. Web 安全
        * 1.13. 约定优于配置支持
        * 1.14. HTTP缓存支持
        * 1.15. 基于代码的 Servlet 容器初始化
        * 1.16. MVC Java 配置，XML 命名空间
    * 2. 视图技术
        * 2.1. 介绍
        * 2.2. Thymeleaf
        * 2.3. Groovy Markup Templates
        * 2.4. FreeMarker
        * 2.5. JSP & JSTL
        * 2.6. Script 模板
        * 2.7. XML 编组视图
        * 2.8. Tiles
        * 2.9. XSLT
        * 2.10. 文档视图（PDF/Exccel）
        * 2.11. Feed 视图
        * 2.12. JSON 映射视图
        * 2.13. XML 映射视图
    * 3. CORS 支持
        * 3.1. 介绍
        * 3.2. 控制器方法的 CORS 配置
        * 3.3. 全局 CORS 配置
        * 3.4. 高级自定义
        * 3.5. 基于 filter 的 CORS 支持
    * 4. 基于 Servlet 的 WebSocket 支持
        * 4.1. 介绍
        * 4.2. WebSocket API
        * 4.3. SockJS 回退选项
        * 4.4. 对 WebSocket 消息架构的 STOMP

-----
* [06.Web 上的 Servlet 和 Reactive 栈-Reactive](06.reactive/README.md)
    * 1. Spring WebFlux
        * 1.1. 介绍
            * 1.1.1 为何使用新的 web 框架
            * 1.1.2 什么是 Reactive 以及为何使用
            * 1.1.3 Reactive API
            * 1.1.4. 编程模型
            * 1.1.5. 选择一个 web 框架
            * 1.1.6. 选择一个服务器
            * 1.1.7. 性能 vs 规模
        * 1.2. Reactive Spring Web
            * 1.2.1. HttpHandler
            * 1.2.2. WebHandler API
            * 1.2.3. 编解码器（Codec）
        * 1.3. DispatcherHandler
            * 1.3.1. 特殊的 Bean 类型
            * 1.3.2. 进程队列
        * 1.4. 注解控制器
            * 1.4.1. @controller 声明
            * 1.4.2. 映射请求
            * 1.4.3. Handler 方法
        * 1.5. 函数式端点
            * 1.5.1. HandlerFunction
            * 1.5.2. RouterFunction
            * 1.5.3. 运行一个服务器
            * 1.5.4. HandlerFilterFunction
        * 1.6. WebFlux 的 Java 配置
            * 1.6.1. 使配置生效
            * 1.6.2. 配置 API
            * 1.6.3. 转换和格式化
            * 1.6.4. 校验
            * 1.6.5. 内容类型解析器
            * 1.6.6. HTTP 信息编解码器
            * 1.6.7. 视图解析器
            * 1.6.8. 静态资源
            * 1.6.9. 路径匹配
            * 1.6.10 自定义配置模式
        * 1.7. WebClient
            * 1.7.1. Retrieve 方法
            * 1.7.2. Exchange 方法
            * 1.7.3. 请求体
            * 1.7.4. 构建选项
            * 1.7.5. 过滤器
        * 1.8. Reactive 资源库

-------
* [07.Kotlin 语言支持](07.kotlin-support/README.md)

-----
* [08.与其他技术的集成](08.integration-with-other-technologies/README.md)

-----
* [09.附录](09.appendix/README.md)

