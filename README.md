See also [associated wiki](https://github.com/NickAger/LearningAWS/wiki)

# LearningAWS for Serverless infrastructure

* [Build your first Serverless Web Application](https://aws.amazon.com/serverless/build-a-web-app/), associated [hacker news discussion](https://news.ycombinator.com/item?id=14740971)
* [serverless.com](http://www.serverless.com)
* [5 AWS mistakes you should avoid](https://cloudonaut.io/5-aws-mistakes-you-should-avoid/)
* [AWS Lambda in Action](https://www.manning.com/books/aws-lambda-in-action)
* [Amazon Web Serices in Plain English](https://www.expeditedssl.com/aws-in-plain-english)
* [A Cloud guru](https://acloud.guru)
* [https://reddit.com/r/amazonwebservices](https://reddit.com/r/amazonwebservices)
* [A cloud guru youTube channel](https://www.youtube.com/channel/UCp8lLM2JP_1pv6E0NQ38pqw)
* [AWS Tips I Wish I'd Known Before I Started](https://wblinks.com/notes/aws-tips-i-wish-id-known-before-i-started/)

# Cognito
* [User Authentication For Web And iOS Apps With AWS Cognito (Part 1)](https://www.smashingmagazine.com/2017/08/user-authentication-web-ios-apps-aws-cognito-part-1/)

# Haskell
* [Deploying Haskell on AWS Lambda](http://www.alfredodinapoli.com/posts/2017-03-16-deploying-haskell-on-aws-lambda.html)
* [Running Haskell code on AWS Lambda](https://github.com/abailly/aws-lambda-haskell)
* [Haskell on AWS Lambda](https://www.agileand.me/haskell-aws-lambda/)
* [Qmuli - Serverless framework for Haskell](https://github.com/qmuli/qmuli/)
* [Haskell EDSL and type-checker for AWS CloudFormation templates](https://github.com/frontrowed/stratosphere)
* [Fugue - Jasper Van der Jeugt works here](https://fugue.co) - https://skillsmatter.com/skillscasts/9879-an-informal-guide-to-better-compiler-errors-jasper-van-der-jeugt
* [Terraform](https://www.terraform.io) - recommended by [fp complete(https://www.fpcomplete.com/blog/2017/08/credstash) - "There are a number of tools that are used for automatic deployment on AWS. Terraform, being one of them, stands out as an amazing tool that allows you to describe your infrastructure as code. It works not just with AWS, but with many other providers". [Why we use Terraform and not Chef, Puppet, Ansible, SaltStack, or CloudFormation](https://blog.gruntwork.io/why-we-use-terraform-and-not-chef-puppet-ansible-saltstack-or-cloudformation-7989dad2865c)

# GraphQL

* [GraphQL with the Serverless Framework](https://serverless.zone/graphql-with-the-serverless-framework-79924829a8ca)
* [A Serverless Blog leveraging GraphQL to offer a REST API with only 1 endpoint using Serverless v0.5](https://github.com/serverless/serverless-graphql-blog)
* [GraphQL for Elm](https://github.com/jahewson/elm-graphql)

## SQL and no-SQL
* [why you probably shouldn't use DynamoDB](https://syslog.ravelin.com/you-probably-shouldnt-use-dynamodb-89143c1287ca) and hacker news [discussion](https://news.ycombinator.com/item?id=14721920)

## General

* [General Info](general.md)

# Elm
* [Uploading to S3 from Elm](http://simonh1000.github.io/2016/12/elm-s3-uploads/)

## bottom-up choreography vs top-down orchestration
> we’re inherently capitalizing on one of the advantages that microservices architectures bring: bottom-up choreography among software modules is much easier to manage than top-down orchestration.

> we should apply best practices from distributed systems. For example, it’s better to avoid synchronous transactions across multiple resources, which are difficult and slow to manage, and design each function to work independently (thanks to event subscriptions) with eventual consistency of data.
 
> Implementing those functionalities as AWS Lambda functions and subscribing those functions to the relevant events allows you to have an efficient architecture that drives updates when something relevant happens in the repositories, without enforcing a centralized workflow of activities that are required when data is changed by the end users. 
