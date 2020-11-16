#### What is QA Tool Kit?

QA Tool Kit is a collection of *libraries*, *tools*, *scripts* and *guides* for your everyday `Quality Assurance (QA)` & `DevOps` tasks. Everything is published as an open source on [Github](https://github.com/qatoolkit) and can be run on Windows, Linux and MacOS.

#### What's in the box?

Currently we provide `.NET Standard` libraries that can be used in your projects or custom applications. More options for other languages like `Python`, `GoLang` might come in the future.

##### 1. [QAToolKit.Core](https://github.com/qatoolkit/qatoolkit-core-net)

This is a core library, that contains shared and core code of the QA Tool Kit project.

Check out the source code and documentation [here](https://github.com/qatoolkit/qatoolkit-core-net).

##### 2.  [QAToolKit.Source.Swagger](https://github.com/qatoolkit/qatoolkit-source-swagger-net)

[Swagger](https://swagger.io/specification/) is a popular OpenAPI specification that defines a standard interface for RESTful APIs. It's a blueprint for humans and machines to explore and generate HTTP requests. 

`QAToolKit.Source.Swagger` can produce a list to HTTP requests from Swagger files which can be used in other steps & processes like load tests, integration tests, etc.

The library is very flexible and allows for request filtering, whitelisting, data generation, URL and model data replacement and basic authentication. This way you can generate requests that can be used in load tests, integration tests, etc.

It supports OpenAPI standard v3.0.

Check out the source code and documentation [here](https://github.com/qatoolkit/qatoolkit-source-swagger-net).

##### 3. [QAToolKit.Engine.Bombardier](https://github.com/qatoolkit/qatoolkit-engine-bombardier-net)

[Bombardier](https://github.com/codesenberg/bombardier) is a fast and easy to use load testing tool written in GoLang. The QA Tool Kit library generates load tests as Bombardier commands and also executes them.
This way we provide an encapsulation and abstraction layer on top of Bombardier executable. And you guessed it, the output of `QAToolKit.Source.Swagger` can be used to generate the load tests.

Check out the source code and documentation [here](https://github.com/qatoolkit/qatoolkit-engine-bombardier-net).

##### 4. [QAToolKit.Engine.HttpTester](https://github.com/qatoolkit/qatoolkit-engine-httptester-net)

The library is a thin wrapper around `HttpClient` and gives you a fluent API to interact with it.

Check out the source code and documentation [here](https://github.com/qatoolkit/qatoolkit-engine-httptester-net).

#### The future is bright

We plan to release more libraries, scripts and guides so stay put and come back in coming months.

**Enjoy! :)**

#### Do you need help?
If you need help with setting up QA Tool Kit within your organization, or you need other of my services contact me through [LinkedIn](https://www.linkedin.com/in/mihajakovac/). I don't bite! :)

I'll setup other communication channels in the future.

#### Legal

All tools are released under [MIT license](https://opensource.org/licenses/MIT).

QA Tool Kit is build on top of other frameworks, tools and libraries. We bow to those individuals and organizations to provide us with tools, without which this project would not be possible.

Copyright (c) 2020 Miha Jakovac