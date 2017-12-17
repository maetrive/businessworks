businessworks-platform 是业务基础集成的平台实现

platform-common 提供平台的一些底层基础类库实现，包括对guice的扩展实现
platform-core 提供平台的一些核心功能实现，比如配置，jndi注册等。
platform-integration 提供apache camel的集成功能
platform-runtime 平台的运行期容器，负责启动平台容器，对容器内被管理对象进行生命周期管理
platform-web 提供平台的元数据已经运行监控的web功能。