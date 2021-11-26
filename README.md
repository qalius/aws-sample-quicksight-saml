# Custom SAML Federation for QuickSight and Google Workspace

This project implements a Lambda integration for custom SAML 2.0-based federation between Google Workspaces and Amazon QuickSight. It contains the solution components described in the blog post [QuickSight integration with G-Suite SSO federation for first-time user setup](https://aws.amazon.com/blogs/PLACEHOLDER).

## Requirements

* [SAM CLI](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-getting-started.html)
* [Node.js](https://nodejs.org/en/)

## Installation

1. Create a new directory called **quicksight-saml** and change to it:
```bash
mkdir quicksight-saml-project && cd quicksight-saml-project
```
2. Initialize a new SAM project:
```bash
sam init
```
3. Select option **2**: **Custom Template Location**
4. Enter this repository URL `https://github.com/qalius/aws-sample-quicksight-saml` as the location
5. Read this blog post for instructions: https://aws.amazon.com/blogs/PLACEHOLDER

## Deploy

To build and deploy this project, run:

```bash
sam build
sam deploy --guided --capabilities CAPABILITY_NAMED_IAM
```

Read this blog post for instructions: https://aws.amazon.com/blogs/PLACEHOLDER

## Cleanup

To delete the deployed resources and artifacts, run and confirm all prompts:

```bash
sam delete
```
