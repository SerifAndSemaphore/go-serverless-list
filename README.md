# Serverless Golang

A list of serverless resources, tools, and frameworks specifically for Golang. Please feel free to fork and send pull requests to include additional links (trying to keep things alphabetically ordered). This list is, in some ways, a subset of https://github.com/ServerlessHeroes/serverless-resources and inspired by some of the other lists out there like https://github.com/avelino/awesome-go and is intended to work the same way (both of those lists you should also check out by the way).

## Frameworks
_Projects with more robust goals than simple deployment._

[λ Gordon](https://github.com/jorgebastida/gordon) - Gordon is a tool to create, wire and deploy AWS Lambdas using CloudFormation

[Apex](https://github.com/apex/apex) - Build, deploy, and manage AWS Lambda functions with ease

[Sparta](http://gosparta.io/) - A Go framework for AWS Lambda microservices

## Discovery & Configuration
_Tools and services for serverless discovery and configuration._

[discfg](https://github.com/tmaiaroto/discfg) - A serverless application configuration tool using Lambda and DynamoDB

## Stand Alone Deployment Tools
_Tools that aren't quite frameworks, but are intended for getting your Go code easily deployed to a serverless provider._

[go-lambda](https://github.com/xlab/go-lambda) - A CLI tool for deploying Go in AWS Lambda

## Snippets

[lambda_proc](https://github.com/jasonmoo/lambda_proc) - One way to run Go in AWS Lambda

[Node.js handler for Go in Lambda](https://gist.github.com/miksago/d1c456d4e235e025791d) - Another way to run Go in AWS Lambda

## Examples & Demos

[go-lambda-geoip](https://github.com/tmaiaroto/go-lambda-geoip) - An example using Node.js to call Go in AWS Lambda to retrieve the requester's IP -> geolocation via API Gateway
