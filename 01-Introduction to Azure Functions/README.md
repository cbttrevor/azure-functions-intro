## Learning Objective

#### Why should you consider using Azure Functions?

* Abstracts away management of underlying hosts
* Lets you focus on your business logic

#### What is Azure Functions comparable to?

* AWS Lambda
* Google Cloud functions

#### How does Azure Functions work?

* Develop your code directly in the Microsoft Azure Portal
* Write and test your code locally, then package and upload into Azure Functions
* In production, a "Scale Controller" is responsible for scaling your function up/down based on demand

#### What pricing plans are available?

* Consumption
    * Max runtime: 10 minutes
* Premium
    * Max runtime: unlimited
    * Minimum one instance always-on
    * Use if app runs continuously 
* App Service
    * Max runtime: unlimited
    * Dedicated capacity for high-usage applications

#### How are Azure Functions triggered?

* HTTP call (any verb)
* Timers, using [ncron .NET library](https://www.nuget.org/packages/NCron/)
  * Gives per-second trigger granularity
* Azure Event Grid
* Service Bus
* Storage blobs and queues

#### What else will you learn in this skill?

* Create an Azure Function in PowerShell
* Schedule Azure Function with Timer
* Handling secrets from Azure functions
* Develop locally with Azure Functions
* Develop a JavaScript Functions app with VSCode and Remote Containers