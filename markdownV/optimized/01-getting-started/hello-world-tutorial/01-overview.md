:doctype: book

include::attributes.txt[]

// Attributes
[.topic]
[#hello-world]
= Tutorial: Create your first \{aws} CDK app
:info_titleabbrev: Create your first CDK app
:info_abstract: Get started with the \{aws} Cloud Development Kit (\{aws} CDK) by using the \{aws} CDK Command Line Interface (\{aws} CDK CLI) to develop your first +
				CDK app, bootstrap your \{aws} environment, and deploy your application on \{aws}.
:keywords: \{aws} CDK, \{aws} Cloud Development Kit (\{aws} CDK), CDK app, \{aws}, \{aws} CloudFormation, Infrastructure as code, IaC

== [abstract]

Get started with the \{aws} Cloud Development Kit (\{aws} CDK) by using the \{aws} CDK Command Line Interface (\{aws} CDK CLI) to develop your first CDK app, bootstrap your \{aws} environment, and deploy your application on \{aws}.
--

// Content start
Get started with using the \{aws} Cloud Development Kit (\{aws} CDK) by using the \{aws} CDK Command Line Interface (\{aws} CDK CLI) to develop your first CDK app, bootstrap your \{aws} environment, and deploy your application on \{aws}.

[#hello-world-prerequisites]
== Prerequisites

Before starting this tutorial, complete all set up steps in xref:getting-started[Getting started with the \{aws} CDK].

[#hello-world-about,hello-world-about.title]
== About this tutorial

In this tutorial, you will create and deploy a simple application on \{aws} using the \{aws} CDK. The application consists of an https://docs.aws.amazon.com/lambda/latest/dg/welcome.html[\{aws} Lambda function] that returns a `Hello World!` message when invoked. The function will be invoked through a https://docs.aws.amazon.com/lambda/latest/dg/lambda-urls.html[Lambda function URL] that serves as a dedicated HTTP(S) endpoint for your Lambda function.

Through this tutorial, you will perform the following:

* _Create your project_ -- Create a CDK project using the CDK CLI `cdk init` command.
* _Configure your \{aws} environment_ -- Configure the \{aws} environment that you will deploy your application into.
* _Bootstrap your \{aws} environment_ -- Prepare your \{aws} environment for deployment by bootstrapping it using the CDK CLI `cdk bootstrap` command.
* _Develop your app_ -- Use constructs from the \{aws} Construct Library to define your Lambda function and Lambda function URL resources.
* _Prepare your app for deployment_ -- Use the CDK CLI to build your app and synthesize an \{aws} CloudFormation template.
* _Deploy your app_ -- Use the CDK CLI `cdk deploy` command to deploy your application and provision your \{aws} resources.
* _Interact with your application_ -- Interact with your deployed Lambda function on \{aws} by invoking it and receiving a response.
* _Modify your app_ -- Modify your Lambda function and deploy to implement your changes.
* _Delete your app_ -- Delete all resources that you created by using the CDK CLI `cdk destroy` command.

