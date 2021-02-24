# Awesome Software Architecture [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

![Twitter URL](https://img.shields.io/badge/-@mehdi_hadeli-%231DA1F2?style=flat-square&logo=twitter&logoColor=ffffff) 
[![blog](https://img.shields.io/badge/blog-dotnetuniversity.com-brightgreen?style=flat-square)](https://dotnetuniversity.com/)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat-square)](./contributing.md)
![Twitter URL](https://img.shields.io/twitter/url?label=Tweet&url=https%3A%2F%2Fgithub.com%2Fmehdihadeli%2Fawesome-software-architecture)

> Collection of useful Articles and resources to learning and practicing about software architecture, patterns and principles. this repository will be updated continuously, keep yourself up to date 

Contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/mehdihadeli/awesome-software-architecture/blob/master/contributing.md) pages first.

Thanks to all [contributors](https://github.com/mehdihadeli/awesome-software-architecture/graphs/contributors), you're awesome and wouldn't be possible without you! The goal is to build a categorized community-driven collection of very well-known resources.

Check out my [blog](https://dotnetuniversity.com) or find me on [Linkedin](https://www.linkedin.com/in/mehdihadeli/) or [Twitter](https://twitter.com/mehdi_hadeli)!

## Contents
- [Software Architecture](#software-architecture)
- [Architectural Style](#architectural-style)
  - [Traditional N-Layer Architecture](traditional-n-layer-architecture)
  - [Clean Architecture](#clean-architecture)
  - [Onion Architecture](#onion-architecture)
  - [Ports And Adapters Architecture (Hexagonal Architecture)](#ports-and-adapters-architecture-hexagonal-architecture-)
  - [Vertical Slice Architecture](#vertical-slice-architecture)
  - [Event Driven Architecture](#event-driven-architecture)
  - [Service Oriented Architecture](#service-oriented-architecture)
- [Architectural Design Principles](#architectural-design-principles)
  - [Crosscutting Concerns](#crosscutting-concerns)
  - [Encapsulation](#encapsulation)
  - [Dependency Inversion](#dependency-inversion)
  - [Interface Segregation Principle](#interface-segregation-principle)
  - [Single Responsibility](#single-responsibility)
  - [Open/Closed Principle](#open/closed-principle)
  - [Command Query Separation](command-query-Separation)
  - [Least Astonishment](#least-astonishment)
  - [Demeter](#demeter)
  - [Favor Composition over Inheritance](favor-composition-over-inheritance)
  - [DRY](#dry)
  - [KISS](#kiss)
  - [YAGNI](#yagni)
  - [Minimize Coupling](#minimize-coupling) 
  - [Maximize Cohesion](#maximize-cohesion) 
  - [Persistence Ignorance](#persistence-ignorance)
  - [GRASP](#grasp)
- [Architectural Patterns](#architectural-patterns)
  - [DDD](#ddd)
  - [CQRS](#cqrs)
  - [MVC](#mvc)
  - [Event Sourcing](#event-sourcing)
  - [Microservices](#microservices)
  - [Serverless-Architecture](#serverless)
- [Design Patterns](#design-patterns)
  - [Decorator](#decorator)
  - [Specification Pattern](#specification-pattern)
  - [Repository Pattern](#repository-pattern)
- [Cloud Design Patterns](#cloud-design-patterns)
  - [Anti-Corruption Layer Pattern](#anti-corruption-layer-pattern)
  - [Asynchronous Request-Reply pattern](#anti-corruption-layer-pattern)
  - [Cache-Aside](#cache-aside)
  - [Command and Query Responsibility Segregation (CQRS)](#command-and-query-responsibility-segregation-(cqrs))
  - [Circuit Breaker](#circuit-breaker)
  - [Gateway Aggregation](#gateway-aggregation)
  - [Gateway Offloading](#gateway-offloading)
  - [Gateway Routing](#gateway-routing)
  - [Priority Queue](#priority-queue)
  - [Publisher/Subscriber](#publisher/subscriber)
  - [Retry](#retry)
  - [Saga](#saga)
  - [Sharding](#sharding)
  - [Sidecar](#sidecar)
  - [Throttling](#throttling)
  - [Valet Key](#valet-key)
  - [At-least-Once Delivery (Outbox Pattern)](#at-least-once-delivery-(outbox-pattern))
  - [Exactly-Once Delivery](#exactly-once-delivery)
- [Object Oriented Design](#object-oriented-design)
- [Distributed Systems Design](#distributed-systems-design)
- [Scalable Software Architecture](#scalable-software-architecture)
- [Clean Code](#clean-code)
- [Anti Patterns](#anti-patterns)
  - [Anemic Domain Model](#anemic-domain-model)
  - [Code Smells](#code-smells)
- [Asynchronous Patterns](#asynchronous-patterns)
- [Modular Monolith](#modular-monolith)
- [Packaging](#packaging)
- [Books](#books)
- [Other Resources](#other-resources)

## Software Architecture

## Resources
- [Modular Monolith](https://files.gotocon.com/uploads/slides/conference_12/515/original/gotoberlin2018-modular-monoliths.pdf)
- [Visualising Software Architecture](http://static.codingthearchitecture.com/visualising-software-architecture.pdf)

### 📝 Articles
- [The Software Architecture Chronicles](https://herbertograca.com/2017/07/03/the-software-architecture-chronicles/)
- [Software Architecture Premises](https://herbertograca.com/2017/07/05/software-architecture-premises/) - Herberto Graca
- [DDD, Hexagonal, Onion, Clean, CQRS, … How I put it all together](https://herbertograca.com/2017/11/16/explicit-architecture-01-ddd-hexagonal-onion-clean-cqrs-how-i-put-it-all-together/) - Herberto Graca
- [Reflecting architecture and domain in code](https://herbertograca.com/2019/06/05/reflecting-architecture-and-domain-in-code/) - Herberto Graca
- [More than concentric layers](https://herbertograca.com/2018/07/07/more-than-concentric-layers/) - Herberto Graca
- [Documenting Software Architecture](https://herbertograca.com/2019/08/12/documenting-software-architecture/) - Herberto Graca
- [Architectural Styles vs. Architectural Patterns vs. Design Patterns](https://herbertograca.com/2017/07/28/architectural-styles-vs-architectural-patterns-vs-design-patterns/)
- [Package by component and architecturally-aligned testing](http://www.codingthearchitecture.com/2015/03/08/package_by_component_and_architecturally_aligned_testing.html)
- [Schools of Package Architecture - An Illustration](http://codemanship.co.uk/parlezuml/blog/?postid=539)
- [Modularity and testability](http://www.codingthearchitecture.com/2014/10/01/modularity_and_testability.html)
- [Software architecture vs code](http://www.codingthearchitecture.com/2014/05/29/software_architecture_vs_code.html)
- [An architecturally-evident coding style](http://www.codingthearchitecture.com/2014/06/01/an_architecturally_evident_coding_style.html)
- [Mapping software architecture to code](http://www.codingthearchitecture.com/2013/04/08/mapping_software_architecture_to_code.html)
- [Components vs classes](http://www.codingthearchitecture.com/2015/03/31/components_vs_classes.html)
- [Simple Sketches for Diagramming your Software Architecture](http://www.methodsandtools.com/archive/softwarearchitecturesketches.php)
- [Architectural Patterns and Styles](https://docs.microsoft.com/en-us/previous-versions/msp-n-p/ee658117(v=pandp.10))
- [Monolithic Architecture](https://herbertograca.com/2017/07/31/monolithic-architecture/)
- [techtribes.je - context](http://www.codingthearchitecture.com/2013/07/09/techtribes_je_context.html)
- [Aligning software architecture and code](http://www.codingthearchitecture.com/2013/07/03/aligning_software_architecture_and_code.html)
- [Component Based Architecture](https://medium.com/omarelgabrys-blog/component-based-architecture-3c3c23c7e348)
- [Layers, hexagons, features and components](https://www.codingthearchitecture.com/2016/04/25/layers_hexagons_features_and_components.html)
- [PresentationDomainDataLayering](https://martinfowler.com/bliki/PresentationDomainDataLayering.html)
- [Layers, hexagons, features and components](http://www.codingthearchitecture.com/2016/04/25/layers_hexagons_features_and_components.html)

### Videos
- [DevTernity 2016: Simon Brown - The Art of Visualising Software Architecture](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=oDpdaXt0HQI&ab_channel=Devoxx)
- [GOTO 2018 • Modular Monoliths • Simon Brown](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=5OjqD-ow8GE&feature=emb_title&ab_channel=GOTOConferences)
- [GOTO 2014 • Software Architecture vs. Code • Simon Brown](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=GAFZcYlO5S0)
- [Modular monoliths (Simon Brown) - 2016](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=h_rBDIC51C4)
- [Modular monoliths by Simon Brown](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=kbKxmEeuvc4)
- [Software architecture and code](https://skillsmatter.com/skillscasts/4312-software-architecture-and-code)
- [Munich .NET Meetup: Modular Monolith Architecture - One to rule them all](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=njDSXUWeik0)
- [Majestic Modular Monoliths by Axel Fontaine](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=BOvxJaklcr0)

## Architectural Style

### Resources
- [Architectural Patterns and Styles](https://docs.microsoft.com/en-us/previous-versions/msp-n-p/ee658117(v=pandp.10)) - Microsoft
- [The Software Architecture Chronicles](https://herbertograca.com/2017/07/03/the-software-architecture-chronicles/) - Herberto Graca
- [DDD, Hexagonal, Onion, Clean, CQRS, … How I put it all together](https://herbertograca.com/2017/11/16/explicit-architecture-01-ddd-hexagonal-onion-clean-cqrs-how-i-put-it-all-together/) - Herberto Graca
- [Reflecting architecture and domain in code](https://herbertograca.com/2019/06/05/reflecting-architecture-and-domain-in-code/) - Herberto Graca
- [More than concentric layers](https://herbertograca.com/2018/07/07/more-than-concentric-layers/) - Herberto Graca
- [Architectural Styles vs. Architectural Patterns vs. Design Patterns](https://herbertograca.com/2017/07/28/architectural-styles-vs-architectural-patterns-vs-design-patterns/)
- [Component Based Architecture](https://medium.com/omarelgabrys-blog/component-based-architecture-3c3c23c7e348)
- [Package by component and architecturally-aligned testing](http://www.codingthearchitecture.com/2015/03/08/package_by_component_and_architecturally_aligned_testing.html)
- [Modular Monolith](https://files.gotocon.com/uploads/slides/conference_12/515/original/gotoberlin2018-modular-monoliths.pdf)
- [The C4 Model](https://c4model.com/)
- [Layers, hexagons, features and components](https://www.codingthearchitecture.com/2016/04/25/layers_hexagons_features_and_components.html)
- [techtribes.je - containers](http://www.codingthearchitecture.com/2013/08/05/techtribes_je_containers.html)
- [techtribes.je - components](http://www.codingthearchitecture.com/2013/08/11/techtribes_je_components.html)
- [PresentationDomainDataLayering](https://martinfowler.com/bliki/PresentationDomainDataLayering.html)
- [Multiple ways of defining Clean Architecture layers](https://proandroiddev.com/multiple-ways-of-defining-clean-architecture-layers-bbb70afa5d4a)
- [Modular Monolith: A Primer](https://www.kamilgrzybek.com/design/modular-monolith-primer/)
- [Layers, hexagons, features and components](http://www.codingthearchitecture.com/2016/04/25/layers_hexagons_features_and_components.html)

### Samples
- [https://github.com/techtribesje/techtribesje](https://github.com/techtribesje/techtribesje)
- [https://github.com/kgrzybek/modular-monolith-with-ddd](https://github.com/kgrzybek/modular-monolith-with-ddd)
- [https://github.com/hgraca/explicit-architecture-php](https://github.com/hgraca/explicit-architecture-php)

### Videos
- [GOTO 2018 • Modular Monoliths • Simon Brown](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=5OjqD-ow8GE&feature=emb_title&ab_channel=GOTOConferences)
- [GOTO 2014 • Software Architecture vs. Code • Simon Brown](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=GAFZcYlO5S0)
- [Modular monoliths (Simon Brown) - 2016](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=h_rBDIC51C4)
- [Modular monoliths by Simon Brown](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=kbKxmEeuvc4)
- [Munich .NET Meetup: Modular Monolith Architecture - One to rule them all](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=njDSXUWeik0)
- [Majestic Modular Monoliths by Axel Fontaine](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=BOvxJaklcr0)
### Traditional N-Layer Architecture

#### 📝 Articles

- [N-tier architecture style](https://docs.microsoft.com/en-us/azure/architecture/guide/architecture-styles/n-tier)
- [Traditional "N-Layer" architecture applications](https://docs.microsoft.com/en-us/dotnet/architecture/modern-web-apps-azure/common-web-application-architectures#traditional-n-layer-architecture-applications)
- [What is N-Tier Architecture? How It Works, Examples, Tutorials, and More](https://stackify.com/n-tier-architecture/)
- [Layered Architecture](https://herbertograca.com/2017/08/03/layered-architecture/) - Herberto Graca

### Clean Architecture

#### 📝 Articles
- [Clean architecture](https://docs.microsoft.com/en-us/dotnet/architecture/modern-web-apps-azure/common-web-application-architectures#clean-architecture) - Microsoft
- [Layers in DDD microservices](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/ddd-oriented-microservice#layers-in-ddd-microservices) - Microsoft
- [The Clean Architecture](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html) - Uncle Bob
- [Clean Architecture: Standing on the shoulders of giants](https://herbertograca.com/2017/09/28/clean-architecture-standing-on-the-shoulders-of-giants/) - Herberto Graca
- [DDD, Hexagonal, Onion, Clean, CQRS, … How I put it all together](https://herbertograca.com/2017/11/16/explicit-architecture-01-ddd-hexagonal-onion-clean-cqrs-how-i-put-it-all-together/) - Herberto Graca
- [Reflecting architecture and domain in code](https://herbertograca.com/2019/06/05/reflecting-architecture-and-domain-in-code/) - Herberto Graca
- [More than concentric layers](https://herbertograca.com/2018/07/07/more-than-concentric-layers/) - Herberto Graca
- [A Brief Intro to Clean Architecture, Clean DDD, and CQRS](https://blog.jacobsdata.com/2020/02/19/a-brief-intro-to-clean-architecture-clean-ddd-and-cqrs) - Jacobs Data
- [A Template for Clean Domain-Driven Design Architecture](https://blog.jacobsdata.com/2020/03/02/a-clean-domain-driven-design-architectural-template) - Jacobs Data
- [Onion Architecture In ASP.NET Core With CQRS – Detailed](https://codewithmukesh.com/blog/onion-architecture-in-aspnet-core/) - CodeWithMukesh
- [CQRS Translated to Clean Architecture](https://blog.fals.io/2018-09-19-cqrs-clean-architecture/)
- [A Brief Intro to Clean Architecture, Clean DDD, and CQRS](https://blog.jacobsdata.com/2020/02/19/a-brief-intro-to-clean-architecture-clean-ddd-and-cqrs)
- [Clean Architecture with .NET Core: Getting Started](https://jasontaylor.dev/clean-architecture-getting-started/)
- [Clean architecture series — Part 3](https://dev.to/pereiren/clean-architecture-series-part-3-2795)
- [Asp.net core series 63 domain model architecture eShopOnWeb project analysis](https://www.itworkman.com/89255.html)
- [Analysis of Equinox open source project under asp.net core series 62 CQRS architecture](https://www.cnblogs.com/MrHSR/p/10820545.html)
- [Equinox open source projects analyzed under the framework CQRS](https://www.programmersought.com/article/81052035363/)
- [Comprehensive understanding of domain model architecture combined with eShopOnWeb](https://www.programmersought.com/article/97275046219/)
- [Clean Architecture - An Introduction](https://www.dandoescode.com/blog/clean-architecture-an-introduction/)
- [Building ASP.NET Core Web APIs with Clean Architecture](https://fullstackmark.com/post/18/building-aspnet-core-web-apis-with-clean-architecture)
- [Clean Architecture for .NET Applications](https://paulovich.net/clean-architecture-for-net-applications/)
- [Hexagonal and Clean Architecture Styles with .NET Core (Reviewed)](https://paulovich.net/hexagonal-and-clean-architecture-styles-with-net-core-reviewed/)
- [ASP.NET Core WebAPI – Clean Architecture](https://codewithmukesh.com/project/aspnet-core-webapi-clean-architecture%e2%80%8b/)
- [Getting Started with Clean Architecture using ASP.NET Core – 01](https://www.gokhan-gokalp.com/en/getting-started-with-clean-architecture-using-asp-net-core-01/) - Gökhan Gökalp
- [Component Based Architecture](https://medium.com/omarelgabrys-blog/component-based-architecture-3c3c23c7e348)
- [Multiple ways of defining Clean Architecture layers](https://proandroiddev.com/multiple-ways-of-defining-clean-architecture-layers-bbb70afa5d4a)
- [Adoption of Clean Architecture layers with modules](https://medium.com/@anil.gudigar/adoption-of-clean-architecture-layers-with-modules-a0b5b9b4e716)

#### 📹 Videos
- [Clean Testing - Clean Architecture with .NET Core - Jason Taylor - NDC Oslo 2020](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=T6NRcX1vnz8) - Jason Taylor
- [Clean Architecture with ASP.NET Core 3.0 - Jason Taylor](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=5OtUm1BLmG0) - Jason Taylor
- [Clean Architecture with ASP.NET Core 2.1](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=_lwCVE_XgqI&feature=w7.mul.ir/yo%7cut%7cu.%7cbe) - Jason Taylor
- [Clean Architecture with ASP.NET Core with Steve "Ardalis" Smith (2020-06-01)](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=joNTQy-KXiU&t=1719s) - Steve Smith
- [SLC.NET Presents: Steve Smith (@Ardalis) - Clean Architecture with ASP.NET Core](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=tYoqmL6e4oY) - Steve Smith
- [Tour of Microsoft's Reference ASP NET Core App eShopOnWeb](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=rSpF1s8wcyA) - Steve Smith
- [An Overview of eShopOnWeb, an ASP.NET Core Reference Application - 2020](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=vRZ8ucGac8M&ab_channel=Ardalis) - Steve Smith
- [Clean Architecture S02](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/playlist?list=PLY9iz4il6pyO46KZN-xQtZZMtdpBO9AoR) - Ivan Paulovich
- [Robert C Martin - Clean Architecture](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=Nltqi7ODZTM&feature=w7.mul.ir/yo%7cut%7cu.%7cbe) - Uncle Bob
- [Gill CLEEREN: Clean architecture with ASP.NET Core | UCP2019](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=BxtHt7tsX-c&t=2582s)

#### 🔖 Samples

- [https://github.com/JacobsDataSolutions/OrgManager](https://github.com/JacobsDataSolutions/OrgManager) - Jacobs Data
    > CQRS and Clean Domain-Driven Design concepts on the ASP.NET Core stack. Demo application for a fictional corporate organization management tool.
    
- [https://github.com/jasontaylordev/CleanArchitecture](https://github.com/jasontaylordev/CleanArchitecture) - Jason Taylor
    > Clean Architecture Solution Template for Angular 10 and .NET 5 - [Project Template (nuget package)](https://www.nuget.org/packages/Clean.Architecture.Solution.Template)

- [https://github.com/EduardoPires/EquinoxProject](https://github.com/EduardoPires/EquinoxProject) - Eduardo Pires
    > Full ASP.NET Core 3.1 application with DDD, CQRS and Event Sourcing concepts

- [https://github.com/ardalis/cleanarchitecture](https://github.com/ardalis/cleanarchitecture) - Steve Smith
    > A starting point for Clean Architecture with ASP.NET Core - [Project Template (visual studio extension)](https://marketplace.visualstudio.com/items?itemName=GregTrevellick.CleanArchitecture)
	
- [https://github.com/dotnet-architecture/eShopOnWeb](https://github.com/dotnet-architecture/eShopOnWeb) - Steve Smith
    > Sample ASP.NET Core 5.0 reference application, powered by Microsoft, demonstrating a layered application architecture with monolithic deployment model. Download the eBook PDF from docs folder.

- [https://github.com/matthewrenze/clean-architecture-demo](https://github.com/matthewrenze/clean-architecture-demo) - Matthew Renze
    > A sample app for my presentation on Clean Architecture: Patterns, Practices, and Principles

- [https://github.com/jasontaylordev/NorthwindTraders](https://github.com/jasontaylordev/NorthwindTraders) - Jason Taylor
    > Northwind Traders is a sample application built using ASP.NET Core and Entity Framework Core.

- [https://github.com/hgraca/explicit-architecture-php](https://github.com/hgraca/explicit-architecture-php) - Herberto Graca
	> This repository is a demo of Explicit Architecture, using the Symfony Demo Application.
	
- [https://github.com/mmacneil/CleanAspNetCoreWebApi](https://github.com/mmacneil/CleanAspNetCoreWebApi) - Mark Macneil
    > Starter project for creating APIs built on ASP.NET Core using clean architecture.

- [https://github.com/ivanpaulovich/clean-architecture-manga](https://github.com/ivanpaulovich/clean-architecture-manga) - Ivan Paulovich
    > Clean Architecture with .NET5, C#9 and React+Redux. Use cases as central organizing structure, completely testable, decoupled from frameworks

- [https://github.com/Daniel-Krzyczkowski/CleanArchitectureWithDevSecOps](https://github.com/Daniel-Krzyczkowski/CleanArchitectureWithDevSecOps) - Daniel Krzyczkowski
    > This repository contains code samples related with clean software architecture and DevSecOps.

- [https://github.com/aspnetcorehero/Boilerplate](https://github.com/aspnetcorehero/Boilerplate) - Mukesh Murugan
    > Clean Architecture Solution Template for ASP.NET Core 5.0. Built with Onion/Hexagonal Architecture and incorporates the most essential Packages your projects will ever need. Includes both WebApi and Web(MVC) Projects.

- [https://github.com/fals/cqrs-clean-eventual-consistency](https://github.com/fals/cqrs-clean-eventual-consistency) - Filipe Augusto
	> CQRS, using Clean Architecture, multiple databases and Eventual Consistency

- [https://github.com/rafaelfgx/Architecture](https://github.com/rafaelfgx/Architecture) - Rafael Garcia
	> Architecture .NET 5, ASP.NET Core 5, Entity Framework Core 5, C# 9, Angular 11, Clean Code, SOLID, DDD.

- [https://github.com/kgrzybek/sample-dotnet-core-cqrs-api](https://github.com/kgrzybek/sample-dotnet-core-cqrs-api) - Kamil Grzybek
	> Sample .NET Core REST API CQRS implementation with raw SQL and DDD using Clean Architecture.

- [https://github.com/phongnguyend/Practical.CleanArchitecture](https://github.com/phongnguyend/Practical.CleanArchitecture)
	> Asp.Net Core 5 Clean Architecture (Microservices, Modular Monolith, Monolith) samples (+Blazor, Angular 11, React 17, Vue 2.6), Domain-Driven Design, CQRS, Event Sourcing, SOLID, Asp.Net Core Identity Custom Storage, Identity Server 4 Admin UI, Entity Framework Core, Selenium E2E Testing, SignalR Notification, Hangfire Tasks Scheduling

- [https://github.com/aspnetrun/run-aspnetcore](https://github.com/aspnetrun/run-aspnetcore) - AspNetRun
	> A starter kit for your next ASP.NET Core web application. Boilerplate for ASP.NET Core reference application, demonstrating a layered application architecture with applying Clean Architecture and DDD
	
- [https://github.com/aspnetrun/run-aspnetcore-cqrs](https://github.com/aspnetrun/run-aspnetcore-cqrs) - AspNetRun
	> Real world Enterprise CRM application example of ASP.NET Core + Angular web application. Implemented CQRS Design Pattern for ASP.NET Core + Angular reference application, demonstrating a layered application architecture with DDD

- [https://github.com/aspnetrun/run-aspnetcore-realworld](https://github.com/aspnetrun/run-aspnetcore-realworld) - AspNetRun
	> E-Commerce real world example of run-aspnetcore ASP.NET Core web application. Implemented e-commerce domain with clean architecture for ASP.NET Core reference application, demonstrating a layered application architecture with DDD best practices.

- [https://github.com/jacobduijzer/CleanArchitectureTemplate](https://github.com/jacobduijzer/CleanArchitectureTemplate)
	> A template for a dotnet core api / mvc "clean architecture" project.

- [https://github.com/CanerPatir/aspnet-core-clean-arch](https://github.com/CanerPatir/aspnet-core-clean-arch)
	> It is a clean architecture project template which is based on hexagonal-architecture principles built with .Net core.
	
- [https://github.com/techtribesje/techtribesje](https://github.com/techtribesje/techtribesje)


### Onion Architecture

#### 📝 Articles

- [Onion Architecture In ASP.NET Core With CQRS – Detailed](https://codewithmukesh.com/blog/onion-architecture-in-aspnet-core/) - CodeWithMukesh
- [Onion Architecture](https://herbertograca.com/2017/09/21/onion-architecture/) - Herberto Graca
- [The Onion Architecture : part 1](https://jeffreypalermo.com/2008/07/the-onion-architecture-part-1) - Jeffrey Palermo
- [The Onion Architecture : part 2](https://jeffreypalermo.com/2008/07/the-onion-architecture-part-2) - Jeffrey Palermo
- [The Onion Architecture : part 3](https://jeffreypalermo.com/2008/08/the-onion-architecture-part-3) - Jeffrey Palermo
- [Onion Architecture: Part 4 – After Four Years](https://jeffreypalermo.com/2013/08/onion-architecture-part-4-after-four-years/) - Jeffrey Palermo
- [Understanding Onion Architecture](https://www.codeguru.com/csharp/csharp/cs_misc/designtechniques/understanding-onion-architecture.html) - Code Guru
- [Clean architecture series — Part 2](https://dev.to/pereiren/clean-architecture-series-part-2-49db) - David Pereira
- [A simple template for Onion Architecture with .NET 5](https://dev.to/pereiren/a-simple-template-for-onion-architecture-with-net-5-3gll) - David Pereira
- [Peeling Back the Onion Architecture](https://blog.tonysneed.com/2011/10/08/peeling-back-the-onion-architecture/) - Tony Sneed

#### 📹 Videos

- [Distributed Onion Architecture - Fort Worth .Net User Group 8/20/2013 - Jeffrey Palermo](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=uuCaXu_kl0U)

#### 🔖 Samples

- [https://github.com/Amitpnk/Onion-architecture-ASP.NET-Core](https://github.com/Amitpnk/Onion-architecture-ASP.NET-Core)
	> WhiteApp API solution template which is built on Onion Architecture with all essential feature using .NET Core!
	
	
### Ports And Adapters Architecture (Hexagonal Architecture)

#### 📝 Articles

- [Ports & Adapters Architecture](https://herbertograca.com/2017/09/14/ports-adapters-architecture/) - Herberto Graca
- [DDD, Hexagonal, Onion, Clean, CQRS, … How I put it all together](https://herbertograca.com/2017/11/16/explicit-architecture-01-ddd-hexagonal-onion-clean-cqrs-how-i-put-it-all-together/) - Herberto Graca
- [Hexagonal architecture](http://web.archive.org/web/20180422210157/http://alistair.cockburn.us/Hexagonal+Architecture) - Alistair Cockburn
- [Hexagonal (Ports & Adapters) Architecture](https://medium.com/@TKonuklar/hexagonal-ports-adapters-architecture-e3617bcf00a0) - Tugce Konuklar
- [HEXAGONAL ARCHITECTURE](https://www.qwan.eu/2020/08/20/hexagonal-architecture.html) - qwan
- [SLICING YOUR CAKE - STRUCTURING YOUR HEXAGONS](https://www.qwan.eu/2021/02/15/slicing-your-cake.html) - qwan
- [Hexagonal Architecture demystified](https://madewithlove.com/blog/software-engineering/hexagonal-architecture-demystified/)
- [Clean architecture series— Part 1](https://pereiren.medium.com/clean-architecture-series-part-1-f34ef6b04b62)
- [Implementing Hexagonal Ports and Adapters Architectural Style](https://amanagrawal.blog/2018/11/17/implementing-hexagonal-ports-and-adapters-architectural-style/)
- [Hexagonal Architecture Style](https://github.com/ivanpaulovich/clean-architecture-manga/wiki/Architecture-Styles#ports-and-adapters-architecture-style) - Ivan Paulovich
- [Ports & Adapters architecture on example](https://wkrzywiec.medium.com/ports-adapters-architecture-on-example-19cab9e93be7)
- [Hexagonal Architecture with Java and Spring](https://reflectoring.io/spring-hexagonal/)
- [Layers, Onions, Ports, Adapters: it's all the same](https://blog.ploeh.dk/2013/12/03/layers-onions-ports-adapters-its-all-the-same/)
- [Ready for changes with Hexagonal Architecture](https://netflixtechblog.com/ready-for-changes-with-hexagonal-architecture-b315ec967749)
- [Hexagonal Architecture](https://fideloper.com/hexagonal-architecture) - Chris Fidao
- [What is Hexagonal Architecture?](https://culttt.com/2014/12/31/hexagonal-architecture/) - PHILIP BROWN
- [Hexagonal != Layers](https://tpierrain.blogspot.com/2016/04/hexagonal-layers.html)
- [Domain-Driven Design and the Hexagonal Architecture](https://vaadin.com/learn/tutorials/ddd/ddd_and_hexagonal)

#### 📹 Videos

- [Chris Fidao - Hexagonal Architecture](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=6SBjKOwVq0o)
- [Hexagonal, Onion, and Explicit Architecture with Elixir - Part 1](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=iGTCZt9Z8A8)

#### 🔖 Samples
- [https://github.com/ivanpaulovich/hexagonal-architecture-acerola](https://github.com/ivanpaulovich/hexagonal-architecture-acerola) - Ivan Paulovich
	> An Hexagonal Architecture service template with DDD, CQRS, TDD and SOLID using .NET Core 2.0. All small features are testable and could be mocked. Adapters could be mocked or exchanged.

- [https://github.com/ivanpaulovich/clean-architecture-manga](https://github.com/ivanpaulovich/clean-architecture-manga) - Ivan Paulovich
	> Clean Architecture with .NET5, C#9 and React+Redux. Use cases as central organizing structure, completely testable, decoupled from frameworks

- [https://github.com/CanerPatir/aspnet-core-clean-arch](https://github.com/CanerPatir/aspnet-core-clean-arch)
	> It is a clean architecture project template which is based on hexagonal-architecture principles built with .Net core.
	
- [https://github.com/Lunch-box/SimpleOrderRouting](https://github.com/Lunch-box/SimpleOrderRouting)
	> Prototype of a Smart Order Routing system (finance). The opportunity for a mob of Lunch-boxers, to explore various technical approaches in reactive programming.
	
### Vertical Slice Architecture

#### 📝 Articles
- [Vertical Slice Architecture](https://jimmybogard.com/vertical-slice-architecture/) - Jimmy Bogard
- [Why vertical slice architecture is better—if you know these few things](https://headspring.com/2019/11/05/why-vertical-slice-architecture-is-better/)
- [Architecting for maintainability through Vertical Slices ](https://www.ghyston.com/insights/architecting-for-maintainability-through-vertical-slices/)
- [Package by component and architecturally-aligned testing](http://www.codingthearchitecture.com/2015/03/08/package_by_component_and_architecturally_aligned_testing.html)
- [Vertical Slices Application Design with MediatR: Part 1](https://www.ojdevelops.com/2017/08/vertical-slices-with-mediatr.html)
- [Organizing Code by Feature using Vertical Slices](https://codeopinion.com/organizing-code-by-feature-using-vertical-slices/) - CodeOpinion
- [Vertical slices in ASP.NET MVC](https://www.kenneth-truyers.net/2016/02/02/vertical-slices-in-asp-net-mvc/)
- [Coding: Packaging by vertical slice](https://markhneedham.com/blog/2012/02/20/coding-packaging-by-vertical-slice/)

#### 📹 Videos
- [Vertical Slice Architecture - Jimmy Bogard](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=5kOzZz2vj2o) - Jimmy Bogard
- [SOLID Architecture in Slices not Layers](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=wTd-VcJCs_M) - Jimmy Bogard
- [DevTernity 2019: Jimmy Bogard – Vertical Slice Architecture](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=T6nglsEDaqA) - Jimmy Bogard

#### Samples
- [https://github.com/jbogard/ContosoUniversityDotNetCore-Pages](https://github.com/jbogard/ContosoUniversityDotNetCore-Pages) - Jimmy Bogard
- [https://github.com/dcomartin/MusicStore](https://github.com/dcomartin/MusicStore) - CodeOpinion
### Event Driven Architecture

#### 📝 Articles
- [Event-driven architecture style](https://docs.microsoft.com/en-us/azure/architecture/guide/architecture-styles/event-driven)
- [Event-Driven Architecture](https://herbertograca.com/2017/10/05/event-driven-architecture/) - Herberto Graca
- [Journey to Event Driven – Part 1: Why Event-First Programming Changes Everything](https://www.confluent.io/blog/journey-to-event-driven-part-1-why-event-first-thinking-changes-everything/)
- [Journey to Event Driven – Part 2: Programming Models for the Event-Driven Architecture](https://www.confluent.io/blog/journey-to-event-driven-part-2-programming-models-event-driven-architecture/)
- [Journey to Event Driven – Part 3: The Affinity Between Events, Streams and Serverless](https://www.confluent.io/blog/journey-to-event-driven-part-3-affinity-between-events-streams-serverless/)
- [Journey to Event Driven – Part 4: Four Pillars of Event Streaming Microservices](https://www.confluent.io/blog/journey-to-event-driven-part-4-four-pillars-of-event-streaming-microservices/)
- [Event Driven Systems](https://medium.com/omarelgabrys-blog/event-driven-systems-cdbe5a4b3d04)

### Service Oriented Architecture

#### 📝 Articles
- [Service Oriented Architecture (SOA)](https://herbertograca.com/2017/11/09/service-oriented-architecture-soa/)


## Architectural Design Principles

### Resources
- [Architectural Styles vs. Architectural Patterns vs. Design Patterns](https://herbertograca.com/2017/07/28/architectural-styles-vs-architectural-patterns-vs-design-patterns/)
- [Architectural principles](https://docs.microsoft.com/en-us/dotnet/architecture/modern-web-apps-azure/architectural-principles) - Microsoft
- [Principles](https://deviq.com/principles/principles-overview) - DevIQ
- [10 Crucial Software Development Principles to Live By](https://www.laneways.agency/software-development-principles/)
- [10 OOP Design Principles Every Programmer Should Know](https://hackernoon.com/10-oop-design-principles-every-programmer-should-know-f187436caf65)
- [Design Principles](https://java-design-patterns.com/principles/) - java-design-patterns.com
- [Principles](http://principles-wiki.net/principles:start) - principles-wiki.net

### Cross Cutting Concerns

#### 📝 Articles
- [Crosscutting Concerns](https://docs.microsoft.com/en-us/previous-versions/msp-n-p/ee658105(v=pandp.10)) - Microsoft
- [A Brief Intro to Clean Architecture, Clean DDD, and CQRS](https://blog.jacobsdata.com/2020/02/19/a-brief-intro-to-clean-architecture-clean-ddd-and-cqrs) - Jacobs Data
- [Managing Cross Cutting Concerns – Logging](https://www.cshandler.com/2015/10/managing-cross-cutting-concerns-logging.html)
- [Cross cutting concern example](https://stackoverflow.com/questions/23700540/cross-cutting-concern-example)
- [cross cutting concern](https://medium.com/anatta-design/cross-cutting-concern-aadf4f51a5c1)
- [Cross-Cutting Concerns for An Enterprise Application](https://dzone.com/articles/cross-cutting-concerns-for-an-enterprise-applicati)
- [Terminology: cross cutting concern](https://crosscuttingconcerns.com/Terminology-cross-cutting-concern)
- [Crosscutting Concerns](https://oncodedesign.com/crosscutting-concerns/)
- [Using the Decorator Pattern to handle cross-cutting concerns](https://www.davideguida.com/using-decorators-to-handle-cross-cutting-concerns/)
- [Chain of Responsibility pattern for handling cross-cutting concerns](https://arturkrajewski.silvrback.com/chain-of-responsibility-pattern-for-handling-cross-cutting-concerns)

### KISS

#### 📝 Articles
- [KISS](https://java-design-patterns.com/principles/#kiss)  - java-design-patterns
- [Principles of Good Programming](https://www.artima.com/weblogs/viewpost.jsp?thread=331531)
- [Keep It Simple Stupid (KISS)](http://principles-wiki.net/principles:keep_it_simple_stupid) - principles-wiki
- [Keep It Simple](https://deviq.com/principles/keep-it-simple) - DevIQ

### YAGNI

#### 📝 Articles
- [YAGNI](https://deviq.com/principles/yagni) - DevIQ
- [YAGNI](https://java-design-patterns.com/principles/#yagni) - java-design-patterns

### Minimize Coupling

#### 📝 Articles
- [Why is loose coupling between services so important?](https://www.ben-morris.com/why-is-loose-coupling-between-services-so-important/) - Ben Morris

### Persistence Ignorance

#### 📝 Articles
- [Persistence Ignorance](https://deviq.com/principles/persistence-ignorance) - DevIQ
- [Understanding Persistence Ignorance Principle](http://techxposer.com/2018/12/29/understanding-persistence-ignorance-principle/)
- [ Infrastructure Ignorance](https://ayende.com/blog/3137/infrastructure-ignorance) - Ayende

### GRASP

#### 📝 Articles
- [GRASP – General Responsibility Assignment Software Patterns Explained](https://www.kamilgrzybek.com/design/grasp-explained/)

## Design Patterns

### Service Locator

#### Articles

- [Service Locator is an Anti-Pattern](https://blog.ploeh.dk/2010/02/03/ServiceLocatorisanAnti-Pattern/)

### Resources 

- [https://github.com/abishekaditya/DesignPatterns](https://github.com/abishekaditya/DesignPatterns)
	> Project : Design Patterns Examples in C#
	
- [https://github.com/anupavanm/csharp-design-patterns-for-humans](https://github.com/anupavanm/csharp-design-patterns-for-humans)
	> Design Patterns for Humans™ - An ultra-simplified explanation - C# Examples
	
- [https://github.com/nemanjarogic/DesignPatternsLibrary](https://github.com/nemanjarogic/DesignPatternsLibrary)
	> A comprehensive design patterns library implemented in C#, which covers various design patterns from the most commonly used ones to the lesser-known ones. Get familiar with and learn design patterns through moderately realistic examples.

### Specification Pattern

#### 📝 Articles
- [Specification pattern: C# implementation](https://enterprisecraftsmanship.com/posts/specification-pattern-c-implementation/) - Vladimir Khorikove
- [Implementing Query Specification pattern in Entity Framework Core](https://gunnarpeipman.com/ef-core-query-specification/) - Gunnar Peipman
- [Using the Specification pattern with Repository and Unit of work](https://dotnetfalcon.com/using-the-specification-pattern-with-repository-and-unit-of-work/) - Akos Nagy

### Repository Pattern

#### 📝 Articles
- [No need for repositories and unit of work with Entity Framework Core](https://gunnarpeipman.com/ef-core-repository-unit-of-work/) - Gunnar Peipman
- [Repository and unit of work ARE useful](https://dotnetfalcon.com/repository-and-unit-of-work-are-useful/) - Akos Nagy
- [The generic repository is just a lazy anti-pattern](https://www.ben-morris.com/why-the-generic-repository-is-just-a-lazy-anti-pattern/)

## Cloud Design Patterns

### Resources
 - [Cloud Design Patterns](https://docs.microsoft.com/en-us/azure/architecture/patterns/index-patterns) - Microsoft
 - [Cloud Computing Patterns](https://www.cloudcomputingpatterns.org) - CloudComputingPatterns
 
###  Anti-Corruption Layer Pattern

###  Asynchronous Request-Reply pattern

###  Cache-Aside

###  Command and Query Responsibility Segregation (CQRS)

###  Circuit Breaker

###  Gateway Aggregation

###  Gateway Offloading

###  Gateway Routing

###  Priority Queue

###  Publisher/Subscriber

###  Retry

###  Saga

###  Sharding

###  Sidecar

###  Throttling

###  Valet Key

### At-least-Once Delivery (Outbox Pattern)

#### 📝 Articles
- [At-least-once Delivery](https://www.cloudcomputingpatterns.org/at_least_once_delivery/) - cloudcomputingpatterns.org
- [The Outbox Pattern](http://www.kamilgrzybek.com/design/the-outbox-pattern/) - Kamil Grzybek
### Exactly-Once Delivery

#### 📝 Articles

- [Exactly-once Delivery](https://www.cloudcomputingpatterns.org/exactly_once_delivery/) - cloudcomputingpatterns.org


## Architectural Patterns

### DDD

#### Core Concepts

##### 📝 Articles
- [Design a DDD-oriented microservice](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/ddd-oriented-microservice) - Microsoft
- [PPPDDD.1 – What is Domain Driven Design?](https://herbertograca.com/2016/08/15/pppddd-1-what-is-domain-driven-design/) - Herberto Graca
- [PPPDDD.2 – Distilling the Problem Domain](https://herbertograca.com/2016/08/22/pppddd-2-distilling-the-problem-domain/) - Herberto Graca
- [PPPDDD.3 – Focusing on the Core Domain](https://herbertograca.com/2016/10/03/pppddd-3-focusing-on-the-core-domain/) - Herberto Graca
- [A Brief Intro to Clean Architecture, Clean DDD, and CQRS](https://blog.jacobsdata.com/2020/02/19/a-brief-intro-to-clean-architecture-clean-ddd-and-cqrs) - Jacobs Data
- [A Basic Intro to Domain-Driven Design](https://blog.jacobsdata.com/2020/02/10/a-basic-intro-to-domain-driven-design) - Jacobs Data
- [A Template for Clean Domain-Driven Design Architecture](https://blog.jacobsdata.com/2020/03/02/a-clean-domain-driven-design-architectural-template) - Jacobs Data
- [Tackling Complexity in the Heart of DDD](https://vladikk.com/2016/04/05/tackling-complexity-ddd/) - Vladik Khononov
- [Strategic Domain-Driven Design](https://vaadin.com/learn/tutorials/ddd/strategic_domain_driven_design)
- [A Basic Intro to Domain-Driven Design](https://medium.com/software-alchemy/a-basic-intro-to-domain-driven-design-bca832c09e9d)
- [DDD and avoiding CRUD](https://stackoverflow.com/questions/23970567/ddd-and-avoiding-crud)
- [Domain-centric vs data-centric approaches to software development](https://enterprisecraftsmanship.com/posts/domain-centric-vs-data-centric-approaches/)
- [Experiences Going From Data-Driven Development to Domain-Driven Design](https://www.infoq.com/news/2013/10/data-driven-to-ddd/)
- [Domain-Driven Design: What is it and how do you use it?](https://airbrake.io/blog/software-design/domain-driven-design)
- [Data Points - Coding for Domain-Driven Design: Tips for Data-Focused Devs](https://docs.microsoft.com/en-us/archive/msdn-magazine/2013/august/data-points-coding-for-domain-driven-design-tips-for-data-focused-devs)
- [Data Points - Coding for Domain-Driven Design: Tips for Data-Focused Devs, Part 2](https://docs.microsoft.com/en-us/archive/msdn-magazine/2013/september/data-points-coding-for-domain-driven-design-tips-for-data-focused-devs-part-2)
- [Data Points - Coding for Domain-Driven Design: Tips for Data-Focused Devs, Part 3](https://docs.microsoft.com/en-us/archive/msdn-magazine/2013/october/data-points-coding-for-domain-driven-design-tips-for-data-focused-devs-part-3)

#### Value Objects

##### 📝 Articles
- [Treating Primitive Obsession with ValueObjects | DDD in .NET](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=h4uldNA1JUE)
- [Implement value objects](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/implement-value-objects)

#### Domain 

##### 📝 Articles
- [Always-Valid Domain Model](https://enterprisecraftsmanship.com/posts/always-valid-domain-model/) - Vladimir Khorikove
- [Domain Model Encapsulation and PI with Entity Framework 2.2](http://www.kamilgrzybek.com/design/domain-model-encapsulation-and-pi-with-entity-framework-2-2/) - Kamil Grzybek
- [Attributes of Clean Domain Model](http://www.kamilgrzybek.com/design/clean-domain-model-attributes/) - Kamil Grzybek
- [Are CQRS commands part of the domain model?](https://enterprisecraftsmanship.com/2019/01/31/cqrs-commands-part-domain-model/) - Vladimir Khorikove
- [Domain model purity vs. domain model completeness](https://enterprisecraftsmanship.com/posts/domain-model-purity-completeness/) - Vladimir Khorikove
- [Design validations in the domain model layer](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/domain-model-layer-validations) - Microsoft
- [Seedwork (reusable base classes and interfaces for your domain model)](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/seedwork-domain-model-base-classes-interfaces) -Microsoft
- [Implement a microservice domain model with .NET](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/net-core-microservice-domain-model) - Microsoft
- [Domain Command Patterns - Validation](https://jimmybogard.com/domain-command-patterns-validation/) - Jimmy Bogard
- [Domain Command Patterns - Handlers](https://jimmybogard.com/domain-command-patterns-handlers/) - Jimmy Bogard

##### 📹 Videos
- [AVOID Entity Services by Focusing on Capabilities](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=2gOOstEI4vU) - CodeOpinion


#### Bounded Context

##### 📝 Articles
- [Context is King: Finding Service Boundaries](https://codeopinion.com/context-is-king-finding-service-boundaries/)
- [Defining Service Boundaries by Splitting Entities](https://codeopinion.com/defining-service-boundaries-by-splitting-entities/)

##### 📹 Videos
- [Context is King | Finding Service Boundaries Talk](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=dnhshUdRW70)
- [Defining Service Boundaries by Splitting Entities](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=lGvYHmvXiyk)

#### Domain Service

##### 📝 Articles

#### Application Service

##### 📝 Articles
- [Domain services vs Application services](https://enterprisecraftsmanship.com/2016/09/08/domain-services-vs-application-services/) - Vladimir Khorikove
- [Implement the microservice application layer using the Web API](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/microservice-application-layer-implementation-web-api) - Microsoft

#### Domain Events

##### 📝 Articles
- [How to publish and handle Domain Events](http://www.kamilgrzybek.com/design/how-to-publish-and-handle-domain-events/) - Kamil Grzybek
- [Handling Domain Events: Missing Part](http://www.kamilgrzybek.com/design/handling-domain-events-missing-part/) - Kamil Grzybek
- [Domain events: design and implementation](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/domain-events-design-implementation) - Microsoft

#### Infrastructure

- [Design the infrastructure persistence layer](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/infrastructure-persistence-layer-design) - Microsoft
- [Implement the infrastructure persistence layer with Entity Framework Core](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/infrastructure-persistence-layer-implementation-entity-framework-core) - Microsoft
- [Use NoSQL databases as a persistence infrastructure](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/nosql-database-persistence-infrastructure) - Microsoft

#### Aggregation

##### 📝 Articles
- [Processing multiple aggregates – transactional vs eventual consistency](https://www.kamilgrzybek.com/design/processing-multiple-aggregates-transactional-vs-eventual-consistency/) - Kamil Grzybek
- [Aggregate (Root) Design: Behavior & Data](https://codeopinion.com/aggregate-root-design-behavior-data/?utm_source=feedly&utm_medium=rss&utm_campaign=aggregate-root-design-behavior-data) - CodeOpinion

##### 📹 Videos
- [Aggregate (Root) Design: Separate Behavior & Data for Persistence](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=GtWVGJp061A) - CodeOpinion

#### Domain Primitives

##### 📝 Articles
- [My Take On Domain Primitives](https://svenhuebner-it.com/my-take-on-domain-primitives/) - Sven Hübner
- [Domain Primitives I: easily declaring domain primitives](https://svenhuebner-it.com/domain-primitives-i-easily-declaring-domain-primitives/) - Sven Hübner 

#### 🔖 Samples

- [https://github.com/dotnet-architecture/eShopOnContainers](https://github.com/dotnet-architecture/eShopOnContainers)
    > Cross-platform .NET sample microservices and container based application that runs on Linux Windows and macOS. Powered by .NET 5, Docker Containers and Azure Kubernetes Services. Supports Visual Studio, VS for Mac and CLI based environments with Docker CLI, dotnet CLI, VS Code or any other code editor.

- [https://github.com/kimcu-on-thenet/ddd-net-ef-core](https://github.com/kimcu-on-thenet/ddd-net-ef-core)
    > Self study: DDD, .net core, entity framework core

- [https://github.com/thangchung/blog-core](https://github.com/thangchung/blog-core) - Thang Chung
    > Modular blog using Blazor with clean domain-driven design patterns

- [https://github.com/thangchung/practical-clean-ddd](https://github.com/thangchung/practical-clean-ddd) Thang Chung
    > The repository uses the eCommerce business domain to demonstrate how to apply Domain Driven Design, Clean Architecture, and Microservice Architecture patterns.

- [https://github.com/ardalis/ddd-guestbook](https://github.com/ardalis/ddd-guestbook) - Steve Smith
    > A DDD guestbook example written for ASP.NET Core
	
- [https://github.com/aspnetrun/run-aspnetcore](https://github.com/aspnetrun/run-aspnetcore) - AspNetRun
	> A starter kit for your next ASP.NET Core web application. Boilerplate for ASP.NET Core reference application, demonstrating a layered application architecture with applying Clean Architecture and DDD

- [https://github.com/aspnetrun/run-aspnetcore-realworld](https://github.com/aspnetrun/run-aspnetcore-realworld) - AspNetRun
	> E-Commerce real world example of run-aspnetcore ASP.NET Core web application. Implemented e-commerce domain with clean architecture for ASP.NET Core reference application, demonstrating a layered application architecture with DDD best practices.

- [https://github.com/itlibrium/DDD-starter-dotnet](https://github.com/itlibrium/DDD-starter-dotnet)
	> Sample implementation and comparison of various approaches to building DDD applications. Useful as a baseline to quickly start a DDD dot net project.

- [https://github.com/JacobsDataSolutions/OrgManager](https://github.com/JacobsDataSolutions/OrgManager)
    > CQRS and Clean Domain-Driven Design concepts on the ASP.NET Core stack. Demo application for a fictional corporate organization management tool.

### CQRS

#### 📝 Articles
- [Command and Query Responsibility Segregation (CQRS) pattern](https://docs.microsoft.com/en-us/azure/architecture/patterns/cqrs) - Microsoft
- [Simple CQRS implementation with raw SQL and DDD](http://www.kamilgrzybek.com/design/simple-cqrs-implementation-with-raw-sql-and-ddd/) - Kamil Grzybek
- [Implement reads/queries in a CQRS microservice](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/cqrs-microservice-reads) - Microsoft
- [Some thoughts on using CQRS without Event Sourcing](https://medium.com/@mbue/some-thoughts-on-using-cqrs-without-event-sourcing-938b878166a2)
- [Tackling Complexity in CQRS](https://vladikk.com/2017/03/20/tackling-complexity-in-cqrs/) - Vladik Khononov
- [From CQS to CQRS](https://herbertograca.com/2017/10/19/from-cqs-to-cqrs/)

#### 🔖 Samples

- [https://github.com/kgrzybek/sample-dotnet-core-cqrs-api](https://github.com/kgrzybek/sample-dotnet-core-cqrs-api) - Kamil Grzybek
	> Sample .NET Core REST API CQRS implementation with raw SQL and DDD using Clean Architecture.
	
- [https://github.com/aspnetrun/run-aspnetcore-cqrs](https://github.com/aspnetrun/run-aspnetcore-cqrs) - AspNetRun
	> Real world Enterprise CRM application example of ASP.NET Core + Angular web application. Implemented CQRS Design Pattern for ASP.NET Core + Angular reference application, demonstrating a layered application architecture with DDD

- [https://github.com/tpierrain/CQRS](https://github.com/tpierrain/CQRS)
	> A simple project to explain CQRS during a live coding session at MS experiences'16
### Event Sourcing

#### 📝 Articles 

- [Event Sourcing](https://martinfowler.com/eaaDev/EventSourcing.html) - Martin Fowler
- [About event sourcing](https://eventuate.io/whyeventsourcing.html) - eventuate.io
- [Event Sourcing pattern](https://docs.microsoft.com/en-us/azure/architecture/patterns/event-sourcing) - Microsoft
- [Event Sourcing Example & Explained in plain English](https://codeopinion.com/event-sourcing-example-explained-in-plain-english/?utm_source=feedly&utm_medium=rss&utm_campaign=event-sourcing-example-explained-in-plain-english) - CodeOpinion

#### Samples

- [https://github.com/PacktPublishing/Hands-On-Domain-Driven-Design-with-.NET-Core](https://github.com/PacktPublishing/Hands-On-Domain-Driven-Design-with-.NET-Core) - Alexey Zimarev

### Microservices

#### Resources
- [Awesome Microservices .NET Core](https://github.com/mjebrahimi/Awesome-Microservices-NetCore) - A collection of awesome training series, Articles, videos, books, courses, sample projects, and tools for Microservices in .NET Core
- [.NET Microservices: Architecture for Containerized .NET Applications](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/) - Microsoft

#### 📝 Articles
- [Microservices architecture: What the gurus say about it](https://herbertograca.com/2017/01/26/microservices-architecture/)
- [Microservices architecture style](https://docs.microsoft.com/en-us/azure/architecture/guide/architecture-styles/microservices)
- [Securing Microservices with IdentityServer4, OAuth2 and OpenID Connect fronted by Ocelot API Gateway](https://medium.com/aspnetrun/securing-microservices-with-identityserver4-with-oauth2-and-openid-connect-fronted-by-ocelot-api-49ea44a0cf9e)
- [Saga Pattern: how to manage distributed transactions with microservices](https://www.cncf.io/blog/2021/02/12/saga-pattern-how-to-manage-distributed-transactions-with-microservices)
- [CAP Theorem, PACELC, and Microservices](https://ardalis.com/cap-pacelc-and-microservices/)

#### 📦 Tools

- [https://github.com/dotnet/tye](https://github.com/dotnet/tye)
    > Tye is a tool that makes developing, testing, and deploying microservices and distributed applications easier. Project Tye includes a local orchestrator to make developing microservices easier and the ability to deploy microservices to Kubernetes with minimal configuration.

#### 🔖 Samples

- [https://github.com/dotnet-architecture/eShopOnContainers](https://github.com/dotnet-architecture/eShopOnContainers)
    > Cross-platform .NET sample microservices and container based application that runs on Linux Windows and macOS. Powered by .NET 5, Docker Containers and Azure Kubernetes Services. Supports Visual Studio, VS for Mac and CLI based environments with Docker CLI, dotnet CLI, VS Code or any other code editor.

- [https://github.com/vietnam-devs/coolstore-microservices](https://github.com/vietnam-devs/coolstore-microservices) - Thang Chung
    > A full-stack .NET microservices build on Dapr and Tye

- [https://github.com/thangchung/practical-dapr](https://github.com/thangchung/practical-dapr) - Thang Chung
    > A full-stack .NET microservices build on Dapr and Tye

- [https://github.com/kimcu-on-thenet/dapr-tye-simple-microservices](https://github.com/kimcu-on-thenet/dapr-tye-simple-microservices)
    > An example of building .NET Core microservices with Dapr and Tye

- [https://github.com/aspnetrun/run-aspnetcore-microservices](https://github.com/aspnetrun/run-aspnetcore-microservices) - AspNetRun
	> Microservices on .Net platforms which used Asp.Net Web API, Docker, RabbitMQ, Ocelot API Gateway, MongoDB, Redis, SqlServer, Entity Framework Core, CQRS and Clean Architecture implementation. See Microservices Architecture and Step by Step Implementation on .NET Course w/ discount
	
- [https://github.com/aspnetrun/run-aspnet-identityserver4](https://github.com/aspnetrun/run-aspnet-identityserver4) - AspNetRun
	> Secure microservices with using standalone Identity Server 4 and backing with Ocelot API Gateway. Protect our ASP.NET Web MVC and API applications with using OAuth 2 and OpenID Connect in IdentityServer4. Securing your web application and API with tokens, working with claims, authentication and authorization middlewares and applying policies.
	
- [https://github.com/alugili/ModernArchitectureShop](https://github.com/alugili/ModernArchitectureShop) - Bassam Alugili
	> The Microservices Online Shop is an application with a modern software architecture that is cleanly designed and based on.NET lightweight technologies. The shop has two build variations. The first variant is the classic Microservices Architectural Style. The second one is with Dapr. Dapr has a comprehensive infrastructure  
	
- [https://github.com/aspnetrun/run-aspnet-grpc](https://github.com/aspnetrun/run-aspnet-grpc) - AspNetRun
	> Using gRPC in Microservices for Building a high-performance Interservice Communication with .Net 5. See gRPC Microservices and Step by Step Implementation on .NET Course w/ discount->

## Object Oriented Design

## Distributed Systems Design

### Resources
- [System Design](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/playlist?list=PLkQkbY7JNJuBoTemzQfjym0sqbOHt5fnV) - Tech Dummies Narendra L
- [Coding and System Design Interview Questions](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/playlist?list=PLA8lYuzFlBqAy6dkZHj5VxUAaqr4vwrka) - Success in Tech
- [System Design](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/playlist?list=PLMCXHnjXnTnvo6alSjVkgxV-VH6EPyvoX) - Gaurav Sen
- [Basics of System Design](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/playlist?list=PLt4nG7RVVk1g_LutiJ8_LvE914rIE5z4u) - Coding Simplified
- [System Design Primer Course](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/playlist?list=PLTCrU9sGyburBw9wNOHebv9SjlE4Elv5a) - sudoCODE
- [System Design And Interview](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/c/interviewingio/videos) - interviewing.io
- [System Design](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/playlist?list=PLhgw50vUymyckXl3D1IlXoVl94wknJfUC) - codeKarle
- [https://github.com/donnemartin/system-design-primer](https://github.com/donnemartin/system-design-primer) - Donne Martin
- [https://github.com/checkcheckzz/system-design-interview](https://github.com/checkcheckzz/system-design-interview) - Zach
- [https://github.com/shashank88/system_design](https://github.com/shashank88/system_design) - shashank khare
- [https://github.com/lei-hsia/grokking-system-design](https://github.com/lei-hsia/grokking-system-design) - LEI XIA

### 📝 Articles
- [Scalable Web Architecture and Distributed Systems](http://www.aosabook.org/en/distsys.html)


## Scalable Software Architecture

### Resources

- [https://github.com/Developer-Y/Scalable-Software-Architecture](https://github.com/Developer-Y/Scalable-Software-Architecture)

## Clean Code

### 📝 Articles

- [10 common broken rules of clean code](http://www.kamilgrzybek.com/clean-code/10-common-broken-clean-code-rules/)

### Resources

- [https://github.com/thangchung/clean-code-dotnet](https://github.com/thangchung/clean-code-dotnet) - Thang Chung 
	> 🛁 Clean Code concepts and tools adapted for .NET
	
## Anti Patterns

### Resources
- [Anti Patterns](https://deviq.com/antipatterns/antipatterns-overview) - DevIQ

### Anemic Domain Model

#### 📝 Articles

- [AnemicDomainModel](https://www.martinfowler.com/bliki/AnemicDomainModel.html)
- [What is Anemic Domain Model and why it can be harmful?](https://danielrusnok.medium.com/what-is-anemic-domain-model-and-why-it-can-be-harmful-2677b1b0a79a) - Daniel Rusnok

### Code Smells

#### 📝 Articles
- [Code Smells](https://deviq.com/antipatterns/code-smells) - DevIQ

## Asynchronous Patterns

### 📝 Articles
- [Communication in a microservice architecture](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/architect-microservice-container-applications/communication-in-microservice-architecture) - Microsoft
- [Asynchronous message-based communication](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/architect-microservice-container-applications/asynchronous-message-based-communication) - Microsoft
- [Modular Monolith: Integration Styles](http://www.kamilgrzybek.com/tag/messaging/) - Kamil Grzybek

## Modular Monolith

### Resources

- [modular-monoliths](https://files.gotocon.com/uploads/slides/conference_12/515/original/gotoberlin2018-modular-monoliths.pdf)

### 📝 Articles
- [Modular Monolith: A Primer](http://www.kamilgrzybek.com/design/modular-monolith-primer/)
- [My experience of using modular monolith and DDD architectures](https://www.thereformedprogrammer.net/my-experience-of-using-modular-monolith-and-ddd-architectures/)
- [Modular Monolith: Architectural Drivers](http://www.kamilgrzybek.com/design/modular-monolith-architectural-drivers/)
- [Modular Monolith: Architecture Enforcement](http://www.kamilgrzybek.com/design/modular-monolith-architecture-enforcement/)
- [MonolithFirst](https://martinfowler.com/bliki/MonolithFirst.html)
- [My experience of using the Clean Code architecture with a Modular Monolith](https://www.thereformedprogrammer.net/my-experience-of-using-the-clean-code-architecture-with-a-modular-monolith/)
- [My experience of using modular monolith and DDD architectures](https://www.thereformedprogrammer.net/my-experience-of-using-modular-monolith-and-ddd-architectures/)

### 🔖 Samples

- [https://github.com/kgrzybek/modular-monolith-with-ddd](https://github.com/kgrzybek/modular-monolith-with-ddd) - Kamil Grzybek
    > Full Modular Monolith application with Domain-Driven Design approach.

- [https://github.com/kgrzybek/modular-monolith-with-ddd-fe-react](https://github.com/kgrzybek/modular-monolith-with-ddd-fe-react) - Kamil Grzybek
    > FrontEnd React application for Modular Monolith With DDD repository and system
	
- [https://github.com/phongnguyend/Practical.CleanArchitecture](https://github.com/phongnguyend/Practical.CleanArchitecture)
	> Asp.Net Core 5 Clean Architecture (Microservices, Modular Monolith, Monolith) samples (+Blazor, Angular 11, React 17, Vue 2.6), Domain-Driven Design, CQRS, Event Sourcing, SOLID, Asp.Net Core Identity Custom Storage, Identity Server 4 Admin UI, Entity Framework Core, Selenium E2E Testing, SignalR Notification, Hangfire Tasks Scheduling

- [https://github.com/dcomartin/LooselyCoupledMonolith](https://github.com/dcomartin/LooselyCoupledMonolith)

### Videos
- [GOTO 2018 • Modular Monoliths • Simon Brown](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=5OjqD-ow8GE&feature=emb_title&ab_channel=GOTOConferences)
- [Modular monoliths (Simon Brown) - 2016](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=h_rBDIC51C4)
- [Modular monoliths by Simon Brown](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=kbKxmEeuvc4)
- [Munich .NET Meetup: Modular Monolith Architecture - One to rule them all](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=njDSXUWeik0)
- [Majestic Modular Monoliths by Axel Fontaine](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=BOvxJaklcr0)
## Packaging

### 📝 Articles
- [Package by component and architecturally-aligned testing](http://www.codingthearchitecture.com/2015/03/08/package_by_component_and_architecturally_aligned_testing.html) - Simon Brown
- [Schools of Package Architecture - An Illustration](http://codemanship.co.uk/parlezuml/blog/?postid=539)

## Books
- [Microsoft Application Architecture Guide, 2nd Edition](https://docs.microsoft.com/en-us/previous-versions/msp-n-p/ff650706(v=pandp.10))
- [Lean Architecture: for Agile Software Development Paperback – Illustrated, 13 July 2010](https://www.amazon.co.uk/Lean-Architecture-Agile-Software-Development/dp/0470684208)
- [Patterns of Enterprise Application Architecture](https://www.amazon.co.uk/Enterprise-Application-Architecture-Addison-Wesley-Signature/dp/0321127420/)
- [Documenting Software Architectures: Views and Beyond](https://www.amazon.co.uk/dp/0321552687)
- [Designing Software Architectures: A Practical Approach](https://www.amazon.co.uk/Designing-Software-Architectures-Practical-Engineering/dp/0134390784)
- [Clean Architecture: A Craftsman's Guide to Software Structure and Design: A Craftsman's Guide to Software Structure and Design](https://www.amazon.co.uk/Clean-Architecture-Craftsmans-Software-Structure/dp/0134494164)
- [Architecting Modern Web Applications with ASP.NET Core and Microsoft Azure](https://ardalis.com/architecture-ebook/)
- [Agile Principles, Patterns, and Practices in C# ](https://www.amazon.com/Agile-Principles-Patterns-Practices-C/dp/0131857258)
- [.NET Microservices: Architecture for Containerized .NET Applications](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/)
- [Software Architecture for Developers](https://leanpub.com/software-architecture-for-developers) - Simon Brown
- [Building Evolutionary Architectures: Support Constant](https://www.amazon.com/Building-Evolutionary-Architectures-Support-Constant/dp/1491986360)
- [Fundamentals of Software Architecture: An Engineering Approach](https://www.amazon.com/Fundamentals-Software-Architecture-Comprehensive-Characteristics/dp/1492043451/ref=pd_lpo_14_t_0/137-5137322-0498527)
- [Just Enough Software Architecture: A Risk-Driven Approach](https://www.amazon.com/Just-Enough-Software-Architecture-Risk-Driven/dp/0984618104)
- [Applying UML and Patterns: An Introduction to Object-Oriented Analysis and Design and Iterative Development](https://www.goodreads.com/book/show/85019.Applying_UML_and_Patterns)
- [Object-Oriented Design Heuristics](https://www.amazon.com/Object-Oriented-Design-Heuristics-paperback-Arthur/dp/0321774965)
- [The Pragmatic Programmer: Your Journey To Mastery](https://www.amazon.com/Pragmatic-Programmer-journey-mastery-Anniversary/dp/0135957052/)
- [Code Complete: A Practical Handbook of Software Construction, Second Edition](https://www.amazon.com/Code-Complete-Practical-Handbook-Construction/dp/0735619670)
- [Cracking the Coding Interview: 189 Programming Questions and Solutions 6th Edition](https://www.amazon.com/Cracking-Coding-Interview-Programming-Questions/dp/0984782850)
- [Building Event-Driven Microservices: Leveraging Organizational Data at Scale](https://www.amazon.com/Building-Event-Driven-Microservices-Leveraging-Organizational/dp/1492057894)
- [System Design Interview – An insider's guide, Second Edition](https://www.amazon.com/System-Design-Interview-insiders-Second/dp/B08CMF2CQF)
- [Designing Distributed Systems: Patterns and Paradigms for Scalable, Reliable Services](https://www.amazon.com/Designing-Distributed-Systems-Patterns-Paradigms/dp/1491983647/)
- [Designing Data-Intensive Applications: The Big Ideas Behind Reliable, Scalable, and Maintainable Systems](https://www.amazon.com/Designing-Data-Intensive-Applications-Reliable-Maintainable/dp/1449373321)
- []()

## Other Resources

- [How to Learn Software Design and Architecture | The Full-stack Software Design & Architecture Map](https://khalilstemmler.com/articles/software-design-architecture/full-stack-software-design/)
- [https://github.com/simskij/awesome-software-architecture](https://github.com/simskij/awesome-software-architecture)
- [https://github.com/Developer-Y/Scalable-Software-Architecture](https://github.com/Developer-Y/Scalable-Software-Architecture)
- [https://github.com/binhnguyennus/awesome-scalability](https://github.com/binhnguyennus/awesome-scalability)
- [https://github.com/mfornos/awesome-microservices](https://github.com/mfornos/awesome-microservices)
- [System Design](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/playlist?list=PLkQkbY7JNJuBoTemzQfjym0sqbOHt5fnV) - Tech Dummies Narendra L
- [Modular Monoliths](https://files.gotocon.com/uploads/slides/conference_12/515/original/gotoberlin2018-modular-monoliths.pdf)
