# Steeltoe 示例应用程序
This repo contains several sample applications illustrating how to use the Steeltoe frameworks. 
> 本仓库包含一系列示例程序来说明如何使用 Steeltoe 框架。

* [Configuration](https://github.com/SteeltoeOSS/Samples/tree/master/Configuration) - various ASP.NET Core and ASP.NET 4.x samples illustrating how to use the Spring Cloud Config Server and access CloudFoundry `VCAP_*` environment variables as configuration data.
    > [Configuration](https://github.com/SteeltoeOSS/Samples/tree/master/Configuration) - 包含 ASP.NET Core 和 ASP.NET 4.x 示例。展示了如何使用 Spring Cloud 配置服务，以及如何将 CloudFoundry 的 `VCAP_*` 环境变量作为配置数据来访问。
* [Connectors](https://github.com/SteeltoeOSS/Samples/tree/master/Connectors) - several samples illustrating how to use the Steeltoe Connectors for connecting to CloudFoundry services in your ASP.NET Core application. Steeltoe Connectors simplify the coding process of binding to and accessing CloudFoundry based services.
    > [Connectors](https://github.com/SteeltoeOSS/Samples/tree/master/Connectors) - 包含大量的示例。展示了在你的 ASP.NET Core 应用程序中，如何使用 Steeltoe Connectors 来连接 CloudFoundry 服务。
* [Discovery](https://github.com/SteeltoeOSS/Samples/tree/master/Discovery) - ASP.NET Core and ASP.NET 4.x sample apps illustrating how to use the Steeltoe discovery packages for Service discovery in micro services based application.
    > [Discovery](https://github.com/SteeltoeOSS/Samples/tree/master/Discovery) - 包含 ASP.NET Core 和 ASP.NET 4.x 示例。展示了在基于微服务的应用程序中，如何使用 Steeltoe 来发现服务。
* [CircuitBreaker](https://github.com/SteeltoeOSS/Samples/tree/master/CircuitBreaker) - ASP.NET Core and ASP.NET 4.x sample apps illustrating how to use the Steeltoe Circuit Breaker packages for building scalable and resilient micro services based application.
    > [CircuitBreaker](https://github.com/SteeltoeOSS/Samples/tree/master/CircuitBreaker) - 包含 ASP.NET Core 和 ASP.NET 4.x 示例。展示了如何使用 Steeltoe Circuit Breaker 工具包来构建可伸缩的、有弹性的微服务应用程序。
* [Security](https://github.com/SteeltoeOSS/Samples/tree/master/Security) - sample apps illustrating how to make use of the Steeltoe CloudFoundry External Security Providers for Authentication and Authorization against a CloudFoundry OAuth2 security service(e.g. UAA Server or Pivotal Single Signon). Also includes a sample illustrating how to make use of a Redis cache for Dataprotection KeyRing storage.
    > [Security](https://github.com/SteeltoeOSS/Samples/tree/master/Security) - 展示了如何使用 Steeltoe 的  CloudFoundry External Security Providers for Authentication and Authorization 来对接 CloudFoundry 的 OAuth2 安全服务（例如：UAA 服务和 Pivotal Single Signon）。并且包含了一个展示如何通过 Redis 缓存来进行数据保护存储的示例。
* [MusicStore](https://github.com/SteeltoeOSS/Samples/tree/master/MusicStore) -  a sample app illustrating how to use all of the Steeltoe components together in a ASP.NET Core application. This is a microservies based application built from the ASP.NET Core reference app MusicStore provided by Microsoft.
    > [MusicStore](https://github.com/SteeltoeOSS/Samples/tree/master/MusicStore) -  展示了如何将各种 Steeltoe 组件集成到一个 ASP.NET Core 应用程序中。该示例由微软提供，是一个用 ASP.NET Core 构建的基于微服务的音乐电商系统。
* [FreddysBBQ](https://github.com/SteeltoeOSS/Samples/tree/master/FreddysBBQ) - a polyglot (i.e. Java and .NET) microservices based sample app illustrating interoperability between Java and .NET based microservices running on CloudFoundry, secured with OAuth2 Security Services and using Spring Cloud Services.
    > [FreddysBBQ](https://github.com/SteeltoeOSS/Samples/tree/master/FreddysBBQ) - 一个跨语言（例如：Java/.NET）的微服务示例。该示例展示了运行在 CloudFoundry 上的 Java 和 .Net 应用程序之间的协作，使用 OAuth2 安全服务来保障安全，使用了 Spring Cloud 服务。

# Branches 分支

All new development is done on the dev branch. More stable versions of the samples can be found on the master branch.
> 所有新的开发都在 dev 分支上。您可以在 master 分支上找到更多稳定版本的示例。

# Documentation 文档

If you are looking for documentation on how to use the Steeltoe components, you can find that [here](http://steeltoe.io/docs/).
> 您可以在[这里](http://steeltoe.io/docs/)找到 Steeltoe 组件的使用文档。

# Building & Running 编译 & 运行

See the Readmes for each sample for instructions on how to build and run.
> 在每个示例中，您可以通过查看 README 来了解如何编译和运行。
