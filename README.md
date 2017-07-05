# LearningAWS for Serverless infrastructure

* [5 AWS mistakes you should avoid](https://cloudonaut.io/5-aws-mistakes-you-should-avoid/)
* [AWS Lambda in Action](https://www.manning.com/books/aws-lambda-in-action)

# Haskell
* [Deploying Haskell on AWS Lambda](http://www.alfredodinapoli.com/posts/2017-03-16-deploying-haskell-on-aws-lambda.html)
* [Running Haskell code on AWS Lambda](https://github.com/abailly/aws-lambda-haskell)
* [Haskell on AWS Lambda](https://www.agileand.me/haskell-aws-lambda/)
* [Qmuli - Serverless framework for Haskell](https://github.com/qmuli/qmuli/)

## General

### The Twelve-factor app
* [The Twelve-factor app](https://12factor.net)

The Twelve factors:
1/ Codebase
One codebase tracked in revision control, many deploys
2. Dependencies
Explicitly declare and isolate dependencies
3. Config
Store config in the environment
4. Backing services
Treat backing services as attached resources
5. Build, release, run
Strictly separate build and run stages
6. Processes
Execute the app as one or more stateless processes
7. Port binding
Export services via port binding
8. Concurrency
Scale out via the process model
9. Disposability
Maximize robustness with fast startup and graceful shutdown
10. Dev/prod parity
Keep development, staging, and production as similar as possible
11. Logs
Treat logs as event streams
12. Admin processes
Run admin/management tasks as one-off processes

# Elm
* [Uploading to S3 from Elm](http://simonh1000.github.io/2016/12/elm-s3-uploads/)

## bottom-up choreography vs top-down orchestration
> we’re inherently capitalizing on one of the advantages that microservices architectures bring: bottom-up choreography among software modules is much easier to manage than top-down orchestration.

> we should apply best practices from distributed systems. For example, it’s better to avoid synchronous transactions across multiple resources, which are difficult and slow to manage, and design each function to work independently (thanks to event subscriptions) with eventual consistency of data.
 
> Implementing those functionalities as AWS Lambda functions and subscribing those functions to the relevant events allows you to have an efficient architecture that drives updates when something relevant happens in the repositories, without enforcing a centralized workflow of activities that are required when data is changed by the end users. 
