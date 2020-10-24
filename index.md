## QA Tool Kit
```
Initial release of QA Tool Kit will is scheduled for
Monday 2nd of November 2020.
```

#### What is QA Tool Kit?

QA Tool Kit is a collection of *libraries*, *tools*, *scripts* and *guides* for your everyday `Quality Assurance (QA)` & `DevOps` tasks. Everything is published as an open source on [Github](https://github.com/qatoolkit) and can be run on Windows, Linux and MacOS.

#### What's in the box?

Currently we provide `.NET Standard` libraries that can be used in your projects, custom applications, etc. More options for other languages like `Python`, `GoLang` might come in the future.

##### 1. QAToolKit.Core

This is a core library, that contains code that is shared and used among the other libraries.

##### 2. QAToolKit.Source.Swagger

[Swagger](https://swagger.io/specification/) is a popular OpenAPI specification that defines a standard interface for RESTful APIs. It's a blueprint for humans and machines to explore and generate HTTP requests. 

`QAToolKit.Source.Swagger` can produce a list to HTTP requests from Swagger files which can be used in other steps & processes like Bombardier (check `QAToolKit.Engine.Bombardier`).

The library is very flexible and allows for request filtering, whitelisting, data generation, URL and model data replacement and basic authentication. This way you can generate requests that can be used in load test, integration test, etc.

It supports OpenAPI standard 3.

##### 3. QAToolKit.Engine.Bombardier

[Bombardier](https://github.com/codesenberg/bombardier) is a fast and easy to use load testing tool written in GoLang. The QA Tool Kit library generates load tests as Bombardier commands and also executes them.
This way we provide an encapsulation and abstraction layer on top of Bombardier executable. And you guessed it, the output of `QAToolKit.Source.Swagger` can be used to generate the load tests.

#### The future is bright

We plan to release more libraries, scripts and guides so stay put and come back in coming months.

**Enjoy! :)**

#### Legal

All tools are released under [MIT license](https://opensource.org/licenses/MIT).

QA Tool Kit is build on top of other frameworks, tools and libraries. We bow to those individuals and organizations to provide us the tools, without which this project would not be possible.

Copyright (c) 2020 Miha Jakovac