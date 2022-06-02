# .NET Core Developer Roadmap 2022

Syd's Roadmap to becoming an [.NET Core](https://docs.microsoft.com/aspnet/core) developer in 2022:

Below you can find a chart demonstrating the paths that I will take and the libraries that I would want to learn to become a better .NET Core developer.

## Disclaimer

> The purpose of this roadmap will guide me through the mentorship programme with the genius [Marcel Michau](https://marcelmichau.dev/). The road map will guide me if I get confused about what to learn next, rather than encouraging me picking what is hip and trendy. I should grow some understanding of why one tool would be better suited for some cases than the other and remember hip and trendy does not always mean best suited for the job

## Objectives
The idea is to be efficient and better at software developing

1. Autonomy – To be in control of what I do, how I do it, and when I do it.
2. And Mastery - To be constantly learning and evolving, becoming a better professional and better human being.
3. Help me become a Full-Stack Engineer – this talks to understanding why certain things are done this way, why and how, not just writing code. Look at architecture, problem solving etc.
4. Knowledge sharing - Learn how to pass on knowledge.
5. Be coming better, efficient at my day-to-day job, understanding the tech, business more.
6. How we will go about some of these goals is through discussions, mini projects to explain concepts as we believe understanding concepts are more important than just knowing how to do xyz in 123. On top of this, I would also apply what I learn from the sessions will have in my day-to-day job.

## Roadmap

1. Learn the prerequisites

   - [C#](https://www.pluralsight.com/paths/csharp)
   - [.NET 6](https://devblogs.microsoft.com/dotnet/announcing-net-6)
   - [Entity Framework](https://www.pluralsight.com/search?q=entity%20framework%20core)
   - [ASP.NET Core](https://www.pluralsight.com/search?q=asp.net%20core)
   - SQL Fundamentals

2. General Development Skills

   - Learn Git, create a few repositories on GitHub, share your code with other people
   - Know HTTP(S) protocol, request methods (GET, POST, PUT, PATCH, DELETE, OPTIONS)
   - Don't be afraid of using Google, [Power Searching with Google](http://www.powersearchingwithgoogle.com)
   - Learn [dotnet CLI](https://docs.microsoft.com/dotnet/core/tools)
   - Read a few books about algorithms and data structures

3. ASP.NET Core Basics

   - [MVC](https://docs.microsoft.com/en-us/aspnet/core/mvc/overview?view=aspnetcore-6.0)
   - [REST](https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-web-api?view=aspnetcore-6.0&tabs=visual-studio)
   - [Authentication](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/?view=aspnetcore-6.0)
   - [Authorization](https://docs.microsoft.com/en-us/aspnet/core/security/authorization/introduction?view=aspnetcore-6.0)
   - [Auth0](https://auth0.com/docs)
   - [OIDC](https://openid.net/connect)

4. SOLID

    - [Single Responsibility Principle (SRP)](https://www.dotnetcurry.com/software-gardening/1148/solid-single-responsibility-principle)
    - [Open-Closed Principle (OCP)](https://www.dotnetcurry.com/software-gardening/1176/solid-open-closed-principle)
    - [Liskov Substitution Principle (LSP)](https://www.dotnetcurry.com/software-gardening/1235/liskov-substitution-principle-lsp-solid-patterns)
    - [Interface Segregation Principle (ISP)](https://www.dotnetcurry.com/software-gardening/1257/interface-segregation-principle-isp-solid-principle)
    - [Dependency Inversion Principle (DIP)](https://www.dotnetcurry.com/software-gardening/1284/dependency-injection-solid-principles)

5. Dependency Injection

   1. DI Containers
      - [Microsoft.Extensions.DependencyInjection](https://docs.microsoft.com/aspnet/core/fundamentals/dependency-injection)
   2. [Life Cycles](https://docs.microsoft.com/aspnet/core/fundamentals/dependency-injection#service-lifetimes)

6. Databases

   1. Relational Databases
      1. [SQL Server](https://www.microsoft.com/sql-server/sql-server-2019)
      2. [MySQL](https://www.mysql.com)
   2. Cloud Databases
      - [CosmosDB](https://docs.microsoft.com/azure/cosmos-db)
   3. NoSQL
      - [MongoDB](https://docs.microsoft.com/aspnet/core/tutorials/first-mongo-app)
      - [LiteDB](https://github.com/mbdavid/LiteDB)
   
7. Object Mapping
    - [AutoMapper](https://github.com/AutoMapper/AutoMapper)  
    
8. Testing

    1. Unit Testing
       1. Frameworks
          - [xUnit](https://docs.microsoft.com/dotnet/core/testing/unit-testing-with-dotnet-test)
          - [NUnit](https://docs.microsoft.com/dotnet/core/testing/unit-testing-with-nunit)
          - [MSTest](https://docs.microsoft.com/dotnet/core/testing/unit-testing-with-mstest)
       2. Mocking
          - [Moq](https://github.com/moq/moq4)
          - [NSubstitute](https://github.com/nsubstitute/NSubstitute)
       3. Assertion
          - [FluentAssertion](https://github.com/fluentassertions/fluentassertions)
    2. Integration Testing
       - [WebApplicationFactory](https://docs.microsoft.com/aspnet/core/test/integration-tests)

9. Microservices

    1. Message-Broker
       - [RabbitMQ](https://www.rabbitmq.com/tutorials/tutorial-one-dotnet.html)
       - [Apache Kafka](https://github.com/confluentinc/confluent-kafka-dotnet)
       - [ActiveMQ](https://github.com/apache/activemq)
       - [Azure Service Bus](https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messaging-overview)
       - [NetMQ](https://github.com/zeromq/netmq)
    2. Message-Bus
       - [MassTransit](https://github.com/MassTransit/MassTransit)
       - [NServiceBus](https://github.com/Particular/NServiceBus)
       - [EasyNetQ](https://github.com/EasyNetQ/EasyNetQ)
       - [CAP](https://github.com/dotnetcore/CAP)
    3. API Gateway
       - [Ocelot](https://github.com/ThreeMammals/Ocelot)
    4. Containerization
       - [Docker](https://www.docker.com)
    5. Orcherstration
       - [Kubernetes](https://kubernetes.io)
    6. Reverse Proxy
       - [YARP](https://github.com/microsoft/reverse-proxy)

10. Continuous Integration & Delivery
    - [GitHub Actions](https://github.com/features/actions)
    - [Azure Pipelines](https://azure.microsoft.com/en-us/services/devops/pipelines)

11. Good to Know

    - [MediatR](https://github.com/jbogard/MediatR)
    - [Fluent Validation](https://github.com/JeremySkinner/FluentValidation)
    - [Polly](https://github.com/App-vNext/Polly)
    - [Nuke](https://github.com/nuke-build/nuke)
    - [Benchmark.NET](https://github.com/dotnet/BenchmarkDotNet)
    - [NodaTime](https://github.com/nodatime/nodatime)
    - [GenFu](https://github.com/MisterJames/GenFu)
    - [Swashbuckle](https://github.com/domaindrivendev/Swashbuckle.AspNetCore)
