# businessworks - 基础业务集成开发平台



businessworks-platform 是业务基础集成的平台实现

platform-common 提供平台的一些底层基础类库实现，包括对guice的扩展实现
platform-core 提供平台的一些核心功能实现，比如配置，jndi注册等。
platform-integration 提供apache camel的集成功能
platform-runtime 平台的运行期容器，负责启动平台容器，对容器内被管理对象进行生命周期管理
platform-web 提供平台的元数据已经运行监控的web功能。


businessworks-link 是业务领域的demo实现

businessworks-extension是业务方的扩展实现




平台化三部曲
       前阿里的电商系统已经形成了一个庞大的生态，各种新老系统，中间件在一起完成业务功能，在维护系统，开发新业务的过程中，感受到了越来越大的压力。旧的系统必须维护改造，新的系统业务能够快速发展，新旧系统之间都需要互联互通，如果我们能有效的在阿里实施EIP，将会对我们系统的架构升级，服务能力，业务快速发展提供保障。请看青霖基于上述思考对平台化开发的探索。
平台化三部曲之一微核心可扩展架构——从Eclipse平台看交易平台化（https://yq.aliyun.com/articles/38）
平台化三部曲之二模块化开发——Google Guice 平台模块化开发的果汁（https://yq.aliyun.com/articles/39）
平台化三部曲之三流程编排——平台化是舞台，流程编排就是导演一场戏（https://yq.aliyun.com/articles/772）


1.基础业务集成开发平台(BusinessWorks) - 概要设计篇
https://yq.aliyun.com/articles/47515

2.基础业务集成开发平台(BusinessWorks) - 业务开发篇
https://yq.aliyun.com/articles/47523



