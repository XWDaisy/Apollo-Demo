# Apollo-Demo
##### * Apollo是什么
>Apollo是一个用于构建数据图的平台，它是一个将应用程序客户端(如React和iOS应用程序)无缝连接到后端服务的通信层


##### * 为什么使用GraphQL

在现代应用程序中管理数据具有挑战性。大多数应用程序要求:

1. 不同的前端客户端，适用于多个平台(web、iOS等)，每个平台都有不同的数据需求
2. 从多个来源(Postgres, Redis等)向客户端提供数据的后端
3. 前端和后端都有复杂的状态和缓存管理

通过采用GraphQL和Apollo，可以大大减少这些挑战。GraphQL的声明式模型可以帮助您创建一个一致的、可预测的API，您可以在所有客户机上使用它。当您添加、删除和迁移后端数据存储时，从客户端的角度来看，API不会发生变化。

##### Resolver
>解析器是一个函数，它负责填充schema中单个字段的数据。每当客户端查询特定字段时，该字段的解析器就会从适当的数据源获取所请求的数据
