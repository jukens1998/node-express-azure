# Node & Express Demo App for Azure DevOps

> Build Your First CI/CD Pipeline using Azure DevOps with this Demo App.

[![Build Status](https://dev.azure.com/juandiegotovaria0759/NodeTestDemom/_apis/build/status/jukens1998.node-express-azure?branchName=master)](https://dev.azure.com/juandiegotovaria0759/NodeTestDemom/_build/latest?definitionId=1&branchName=master)

This is a Node and Express web application used to demonstrate CI/CD with Azure DevOps. You can clone this repo and use it within Azure DevOps to build, test, and release to an Azure App Service web app.

## Running and Testing Locally:

You can use these commands to install, test, and run the app locally. (Not Required)

### Install

```
npm install
```

### Test

```
npm test
```

![alt text](https://user-images.githubusercontent.com/5126491/51065379-c1743280-15c1-11e9-80fd-6a3d7ab4ac1b.jpg "Unit Test")

Navigate to the `/test` folder to review the unit tests for this project. These tests will run as part of your Azure DevOps Build pipeline. See `azure-pipelines.yml` in this repo.

### Start

```
npm start
```


### Version

1.0.0

### License

This project is licensed under the Apache License 2.0
