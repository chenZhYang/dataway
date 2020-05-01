# dataway
Dataway和springboot结合使用
Dataway介绍
Dataway 是基于 DataQL 服务聚合能力，为应用提供的一个接口配置工具。使得使用者无需开发任何代码就配置一个满足需求的接口。整个接口配置、测试、冒烟、发布。一站式都通过 Dataway 提供的 UI 界面完成。UI 会以 Jar 包方式提供并集成到应用中并和应用共享同一个 http 端口，应用无需单独为 Dataway 开辟新的管理端口。
这种内嵌集成方式模式的优点是，可以使得大部分老项目都可以在无侵入的情况下直接应用 Dataway。进而改进老项目的迭代效率，大大减少企业项目研发成本。
Dataway 工具化的提供 DataQL 配置能力。这种研发模式的变革使得，相当多的需求开发场景只需要配置即可完成交付。从而避免了从数据存取到前端接口之间的一系列开发任务，例如：Mapper、BO、VO、DO、DAO、Service、Controller 统统不在需要。
Dataway 是 Hasor 生态中的一员，因此在 Spring 中使用 Dataway 首先要做的就是打通两个生态。根据官方文档中推荐的方式我们将 Hasor 和 Spring Boot 整合起来。这里是原文：https://www.hasor.net/web/extends/spring/for_boot.html
