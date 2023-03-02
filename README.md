# .NET Tools in use 👾

A collection code snippets of libraries, tools, and frameworks that you can use in your project.

<br />

## Content
- [.NET Tools in use 👾](#net-tools-in-use-)
  - [Content](#content)
    - [Official docs](#official-docs)
    - [API](#api)
    - [Web](#web)
    - [Mobile](#mobile)
    - [Database](#database)
    - [ORM](#orm)
    - [Logging](#logging)
      - [Libraries](#libraries)
      - [Cloud solutions](#cloud-solutions)

### Official docs

### API
* ASP.NET Core: This is a popular framework for building APIs in .NET. It provides a lightweight, modular approach to building web applications and supports both RESTful and RPC-style APIs.

* NancyFX: This is a lightweight, low-ceremony framework for building HTTP-based services on .NET and .NET Core.

* ServiceStack: This is a high-performance, modular framework for building RESTful services using C# and .NET.

* RestSharp: This is a simple and lightweight REST client for .NET that allows you to easily consume RESTful APIs.

* GraphQL .NET: This is a library that allows you to build APIs using the GraphQL query language. It provides a type-safe way to query your data and allows clients to specify exactly what data they need.

* OData: This is a protocol for building and consuming RESTful APIs that are queryable using a standard set of query parameters. The OData .NET library allows you to easily create and consume OData services.

* Microsoft.AspNet.WebApi: This is a framework for building HTTP services that can be consumed by a wide range of clients, including browsers, mobile devices, and desktop applications. It provides features such as routing, content negotiation, and model binding.

### Web
* ASP.NET Core: This is a popular framework for building web applications and APIs in .NET. It provides a lightweight, modular approach to building web applications and supports both server-side and client-side rendering.

* Blazor: This is a web UI framework for building single-page applications (SPAs) using .NET and C#. It allows you to build interactive client-side web applications using C# instead of JavaScript.

* Razor Pages: This is a page-based web development model for building web applications with .NET. It provides a lightweight, code-focused approach to building web UIs using Razor syntax.

* Angular: This is a popular front-end web development framework that can be used with .NET. It provides a powerful set of tools for building complex, dynamic web UIs.

* React: This is a popular front-end web development library that can be used with .NET. It provides a lightweight, efficient way to build reusable UI components.

* Vue.js: This is a progressive JavaScript framework for building user interfaces. It can be used with .NET to build dynamic, reactive web UIs.

### Mobile
* Xamarin: This is a popular framework for building native mobile applications for iOS and Android using C#. It allows you to share code between platforms and provides access to the native APIs of each platform.
  * Telerik UI for Xamarin: This is a set of UI controls and components for building native mobile applications with Xamarin. It includes a wide range of controls for building data grids, charts, calendars, and more.

  * Syncfusion Xamarin UI Controls: This is another set of UI controls and components for building native mobile applications with Xamarin. It includes a wide range of controls for building data grids, charts, calendars, and more, and also includes built-in support for internationalization and accessibility.

  * Prism: This is a framework for building modular, scalable, and maintainable applications with .NET. It provides a set of tools and libraries for building mobile applications with Xamarin.

* .NET MAUI: This is a new framework for building native mobile applications for iOS, Android, and Windows using .NET. It provides a single codebase that can be shared across platforms and includes a set of built-in controls and components.

* Uno Platform: This is a framework for building cross-platform mobile applications using .NET and XAML. It allows you to write code once and deploy it to iOS, Android, and Windows platforms.

* MvvmCross: This is a cross-platform MVVM framework for building mobile applications with .NET. It allows you to write code once and deploy it to multiple platforms, including iOS, Android, and Windows.

* React Native: This is a popular framework for building cross-platform mobile applications using React. It allows you to write code once and deploy it to both iOS and Android platforms.
### Database
* Microsoft SQL Server: This is a popular relational database management system (RDBMS) developed by Microsoft. It is commonly used with .NET and provides advanced features such as transaction management, data compression, and in-memory processing.

* MySQL: This is an open-source RDBMS that is widely used with .NET. It is known for its scalability, performance, and ease of use.

* PostgreSQL: This is another open-source RDBMS that is popular with .NET developers. It is known for its reliability, robustness, and support for advanced features such as JSON data types and full-text search.

* Oracle Database: This is a powerful RDBMS developed by Oracle Corporation. It is commonly used in enterprise applications and provides advanced features such as partitioning, clustering, and high availability.

* MongoDB: This is a popular NoSQL database that is widely used with .NET. It is known for its scalability, flexibility, and support for unstructured data.

* Redis: This is an in-memory key-value store that is commonly used as a cache or message broker. It is known for its high performance, low latency, and support for advanced data structures. 


* SQLite: This is a lightweight, file-based relational database that is commonly used in mobile and desktop applications. It is known for its simplicity, portability, and support for transactions.

### ORM
* Entity Framework (EF): This is a popular ORM framework developed by Microsoft that can be used with various databases such as Microsoft SQL Server, MySQL, PostgreSQL, SQLite, and Oracle. EF allows developers to work with data in the form of objects and provides features such as LINQ, change tracking, and automatic mapping of database tables to objects.

* NHibernate: This is a powerful ORM framework that can be used with various databases such as Microsoft SQL Server, MySQL, PostgreSQL, and Oracle. NHibernate provides features such as lazy loading, caching, and transaction management, and supports various mapping strategies for mapping objects to database tables.

* Dapper: This is a lightweight ORM framework developed by StackExchange that can be used with various databases such as Microsoft SQL Server, MySQL, PostgreSQL, SQLite, and Oracle. Dapper provides a fast and easy-to-use way of executing SQL queries and mapping query results to objects.

* LINQ to SQL: This is an ORM framework developed by Microsoft that can be used with Microsoft SQL Server. LINQ to SQL allows developers to work with data in the form of objects and provides features such as automatic mapping of database tables to objects and support for LINQ queries.

* LLBLGen Pro: This is a commercial ORM framework that can be used with various databases such as Microsoft SQL Server, MySQL, PostgreSQL, SQLite, and Oracle. LLBLGen Pro provides a visual designer for creating data models and supports various mapping strategies for mapping objects to database tables.

### Logging

#### Libraries
* Serilog: Serilog is a flexible and structured logging library for .NET that supports various logging sinks such as text files, databases, and message queues. Serilog provides advanced features such as log levels, structured logging, and filtering.

* NLog: NLog is a mature and highly configurable logging library for .NET that supports various logging targets such as files, databases, and email. NLog provides advanced features such as log levels, log rotation, and custom layout rendering.

* log4net: log4net is a popular logging library for .NET that provides a range of logging features such as log levels, logging to files and databases, and logging via email. log4net is highly configurable and can be customized using code or configuration files.

* Microsoft.Extensions.Logging: Microsoft.Extensions.Logging is a logging library that is part of the .NET Core runtime. It provides a lightweight logging API that can be used with various logging providers such as Serilog, NLog, and log4net. Microsoft.Extensions.Logging provides features such as log levels, structured logging, and dependency injection.

* Elmah: Elmah is an error logging library for .NET that can be used to log errors and exceptions in web applications. Elmah provides a range of features such as email alerts, error filtering, and detailed error reports.


#### Cloud solutions
* Azure Application Insights: Azure Application Insights is a logging and monitoring service for .NET applications that is part of the Azure cloud platform. Application Insights provides rich application monitoring and analytics features such as log collection, performance monitoring, and exception tracking.

* AWS CloudWatch Logs: AWS CloudWatch Logs is a logging service for .NET applications that is part of the AWS cloud platform. CloudWatch Logs provides log collection, monitoring, and analysis features, as well as integration with other AWS services such as Lambda and EC2.

* Seq: Seq is a centralized logging and analytics platform for .NET applications that can be deployed on-premises or in the cloud. Seq provides advanced logging features such as structured logging, log searching, and real-time log streaming.

* Stackify Retrace: Stackify Retrace is a cloud-based logging and performance monitoring tool for .NET applications. Retrace provides log collection, monitoring, and analysis features, as well as application performance monitoring, error tracking, and alerting.

* Loggly: Loggly is a cloud-based logging service that can be used with .NET applications. Loggly provides features such as log collection, searching, and analysis, as well as integration with other cloud services such as AWS and Azure.