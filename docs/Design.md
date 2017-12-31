

1. 平台架构

> 平台架构将采用微内核和插件扩展的架构，通过模块化技术，将平台的能力分层次透出。首先这个平台需要一个稳定的微内核Runtime，提供平台核心的能力，如扩展机制，插件模块管理等。在这个内核之上，平台提供一个基础集成平台，用于协调平台各组件协作，流程管理等。这个基础平台和微内核将构成平台的基石，然后在这些基础上，我们将构建业务领域平台，在这一层，定义业务领域相关的模型，功能点，业务原型等。最后业务方可以方便的利用平台的能力，构建自己特定的业务，满足业务需要。

![Image text](暂无)