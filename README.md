# Serverless Golang

A list of serverless resources, tools, and frameworks specifically for Golang. Please feel free to fork and send pull requests to include additional links (trying to keep things alphabetically ordered). This list is, in some ways, a subset of https://github.com/ServerlessHeroes/serverless-resources and inspired by some of the other lists out there like https://github.com/avelino/awesome-go and is intended to work the same way (both of those lists you should also check out by the way).

# Platforms & Services
_Serverless platforms and services that support Go (where you can run your functions)_

[AWS Lambda](https://aws.amazon.com/lambda) - AWS Lambda will allow Go through a wrapper (see tools below)

[Hyper.sh](https://console.hyper.sh/register/invite/4DWLbzRrPYumMW47jyLACr6zwqRNJNcO) - Hyper.sh allows you to run Docker containers billed by the second and is a fully managed PaaS...and those are the reasons why it's roped in with "serverless" (shameless full disclosure: my referral code in URL)

[Iron Functions](https://github.com/iron-io/functions) - Iron.io has open sourced it's Functions platform which lets you run Docker container to run functions

[Microsoft Azure Functions]() - Azure Functions will allow Go through a wrapper similar to AWS Lambda

[OpenFaaS - Functions as a Service](https://github.com/openfaas/faas) - Serverless platform/framework for Kubernetes, Docker Swarm, Hyper.sh, DC/OS and Rancher

## Frameworks
_Projects with more robust goals than simple deployment._

[λ Gordon](https://github.com/jorgebastida/gordon) - Gordon is a tool to create, wire and deploy AWS Lambdas using CloudFormation

[Apex](https://github.com/apex/apex) - Build, deploy, and manage AWS Lambda functions with ease

[Fnproject](https://github.com/fnproject/fn) - The container native, cloud agnostic serverless platform.

[Golang Serverless](https://github.com/yunspace/serverless-golang) - Golang support for [Serverless](https://serverless.com/) framework

[Sparta](http://gosparta.io/) - A Go framework for AWS Lambda microservices

## Discovery & Configuration
_Tools and services for serverless discovery and configuration._

[discfg](https://github.com/tmaiaroto/discfg) - A serverless application configuration tool using Lambda and DynamoDB

## Stand Alone Deployment Tools
_Tools that aren't quite frameworks, but are intended for getting your Go code easily deployed to a serverless provider._

[Aegis](https://github.com/tmaiaroto/aegis) - A tool for deploying AWS Lambda Proxy with API Gateway (allows your Lambda to handle any RESTful requests via API Gateway's `ANY` method)

[azul](https://github.com/wbuchwalter/azul) - A tool for deploying and running Go in Microsoft Azure Functions

[cloudfunc](https://github.com/flowup/cloudfunc) - Deploying Google Cloud Functions written in Golang with ease

[eawsy AWS Lambda - Go](https://github.com/eawsy/aws-lambda-go) - A tool for deploying Go in AWS Lambda using Python for speed

[go-lambda](https://github.com/xlab/go-lambda) - A CLI tool for deploying Go in AWS Lambda

## Snippets

[lambda_proc](https://github.com/jasonmoo/lambda_proc) - One way to run Go in AWS Lambda using Node.js

[Node.js handler for Go in Lambda](https://gist.github.com/miksago/d1c456d4e235e025791d) - Another way to run Go in AWS Lambda

[AWS Lambda Binary](https://www.npmjs.com/package/aws-lambda-binary) - Run any compiled binary on AWS Lambda over standard input and output for maximum flexibility. 5 lines of code to get started with your lambda.

## Examples & Demos

[go-lambda-geoip](https://github.com/tmaiaroto/go-lambda-geoip) - An example using Node.js to call Go in AWS Lambda to retrieve the requester's IP -> geolocation via API Gateway
