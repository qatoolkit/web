## QA Tool Kit
```
Initial release of QA Tool Kit will is scheduled for
Monday 2nd of November 2020.
```

#### What is QA Tool Kit?

QA Tool Kit is a collection of libraries, tools, scripts and guides for your everyday Quality Assurance (QA) & DevOps tasks. Every tool is published as an open source on [Github](https://github.com/qatoolkit). It can be run on Windows, Linux and MacOS.

#### What's in the box?

Currently we provide .NET Standard libraries that can be used in your projects, custom applications, etc.

##### QAToolKit.Core

This is a core library, that contains code that is shared and used among the other libraries.

##### QAToolKit.Source.Swagger

[Swagger](https://swagger.io/specification/) is a popular Open Web API documentation standard and is a used as a blueprint to generate HTTP requests. Those can then be used in other processes like Bombardier below.

A library is very flexible and allow for filtering of requests, whitelisting, data generation, URL and model data replacement and basic authentication. It supports OpenAPI standard 3.

##### QAToolKit.Engine.Bombardier

[Bombardier](https://github.com/codesenberg/bombardier) is a fast and easy to use load testing tool written in GoLang. The QA Tool Kit library generates load tests as Bombardier commands and also executes them.
This way we provide an encapsulation and abstraction layer on top of Bombardier executable. And you guessed it, the output of `QAToolKit.Source.Swagger` can be used to generate the load tests.

#### The future is bright

We plan to produce more libraries, scripts and guides so stay put and come back in coming months.