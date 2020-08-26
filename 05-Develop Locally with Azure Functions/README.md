## Learning Objective

Although it's possible to develop Azure functions in the Azure portal, this isn't the best solution.
If you are developing inside of a git repository, it's faster to develop and test your code locally, before pushing it to run in Azure.
Using a local development cycle also gives you the freedom to work anywhere without an Internet connection.

## What You'll Need

* Install Node.js and npm
* Install Azure Functions Core Tools
    * `npm install --global azure-functions-core-tools@3`
* Azure Functions extension for Visual Studio Code

## Process

1. Create new Azure Functions project in Visual Studio Code
1. Download the app settings, if required `func azure functionapp fetch-app-settings <FunctionAppName>`
1. Use VSCode or `func` CLI to create new function
1. Run `func start` in the project folder
