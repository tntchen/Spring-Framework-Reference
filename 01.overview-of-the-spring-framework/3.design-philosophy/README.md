# 3. 设计理念

当你学习一个框架的时候，重要的是不仅要知道它做了什么，还要知道它遵循的原则。下面是 Spring 框架设计的指导原则：

* 在每个层次上提供选择。Spring 允许用户尽可能晚地推迟设计决策。例如，用户可以在不改变代码的情况下通过配置切换数据持久化提供者。对于许多其他的基础设施问题和与第三方 api 的集成也是如此。
* 容纳不同的观点。Spring 拥抱灵活性，对应该如何做是不会固执己见。它以不同的视角支持广泛的应用程序需求。
* 保持健壮的向后兼容性。Spring 的进化经过了精心的管理，在不同版本之间几乎没有发生什么变化。Spring 支持精心选择的JDK 版本和第三方库，以促进依赖于Spring 的应用程序和库的维护。
* 关注 API 设计。Spring团队花了大量的思考和时间来制作直观的 api，并且在许多版本和许多年的时间里都能保持这种状态。
* 为代码质量设置高标准。Spring框架非常强调有意义的、当前的和准确的 Javadoc。它是少数几个能够声明干净的代码结构的项目之一，在包之间没有循环依赖关系。

