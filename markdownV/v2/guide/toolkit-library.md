include::attributes.txt[]

// Attributes

[.topic]
[#toolkit-library]
= Perform programmatic actions using the CDK Toolkit Library
:info_titleabbrev: Use the CDK Toolkit Library
:keywords: CDK Toolkit Library, Programmatic access, \{aws} CDK, \{aws} Cloud Development Kit (\{aws} CDK), deploy, \{aws} CloudFormation, Infrastructure as Code, synthesize

== [abstract]

The \{aws} Cloud Development Kit (\{aws} CDK) Toolkit Library enables you to perform CDK actions programmatically instead of using the CLI.
--

// Content start

[#toolkit-library-intro]
== Understanding the CDK Toolkit Library

The CDK Toolkit Library enables you to perform CDK actions programmatically through code instead of using CLI commands. You can use this library to create custom tools, build specialized CLI applications, and integrate CDK capabilities into your development workflows.

_Manage your infrastructure lifecycle with programmatic control_::

The CDK Toolkit Library provides programmatic interfaces for the following CDK actions:
+
--

* _Synthesis_ - Generate \{aws} CloudFormation templates and deployment artifacts.
* _Deployment_ - Provision or update infrastructure using CloudFormation templates.
* _List_ - View information about stacks and their dependencies.
* _Watch_ - Monitor CDK apps for local changes.
* _Rollback_ - Return stacks to their last stable state.
* {blank}
+
== _Destroy_ - Remove CDK stacks and associated resources.

_Enhance and customize your infrastructure management_::
+
--

* _Control through code_ - Integrate infrastructure management directly into your applications and build responsive deployment pipelines.
* _Manage cloud assemblies_ - Create, inspect, and transform your infrastructure definitions before deployment.
* _Customize deployments_ - Configure parameters, rollback behavior, and monitoring to match your requirements.
* _Handle errors precisely_ - Implement structured error handling with detailed diagnostic information.
* _Tailor communications_ - Configure custom progress indicators and logging through `IoHost` implementations.
* {blank}
+
== _Connect with \{aws}_ - Configure profiles, Regions, and authentication flows programmatically.

[#toolkit-library-intro-when]
== Choosing when to use the CDK Toolkit Library

The CDK Toolkit Library is particularly valuable when you need to:

* Automate infrastructure deployments as part of CI/CD pipelines.
* Build custom deployment tools tailored to your organization's needs.
* Integrate CDK actions into existing applications or platforms.
* Create specialized deployment workflows with custom validation or approval steps.
* Implement advanced infrastructure management patterns across multiple environments.

[#toolkit-library-intro-example]
== Using the CDK Toolkit Library

The following example shows how to create and deploy a simple S3 bucket using the CDK Toolkit Library:

== [source, typescript, subs="verbatim,attributes"]

// Import required packages
import { Toolkit } from '@aws-cdk/toolkit-lib';
import { App, Stack } from 'aws-cdk-lib';
import * as s3 from 'aws-cdk-lib/aws-s3';

// Create and configure the CDK Toolkit
const toolkit = new Toolkit();

// Create a cloud assembly source with an inline app
const cloudAssemblySource = await toolkit.fromAssemblyBuilder(async () \=> {
   const app = new App();
   const stack = new Stack(app, 'SimpleStorageStack');

// Create an S3 bucket in the stack
   new s3.Bucket(stack, 'MyFirstBucket', {
      versioned: true
   });

return app.synth();
});

// Deploy the stack
await toolkit.deploy(cloudAssemblySource);
---

_What you can do next_::
+
--

* _Automate deployments_ - Trigger deployments programmatically and add pre/post deployment steps.
* _Integrate with systems_ - Connect with CI/CD workflows, custom tools, and monitoring solutions.
* _Control deployment details_ - Configure fine-grained options for stack selection and multi-environment deployments.
* {blank}
+
== _Enhance reliability_ - Implement production-ready error handling and deployment progress tracking.

[#toolkit-library-intro-next]
== Next steps

To begin using the CDK Toolkit Library, see xref:toolkit-library-gs[Get started with the CDK Toolkit Library].

[#toolkit-library-intro-learn]
== Learn more

To learn more about the CDK Toolkit Library, see the following:

* link:https://www.npmjs.com/package/@aws-cdk/toolkit-lib[ReadMe] in the _@aws-cdk/toolkit-lib_ `npm` package.
* link:https://docs.aws.amazon.com/cdk/api/toolkit-lib/[\{aws} CDK Toolkit Library API Reference].

include::toolkit-library-gs.adoc[leveloffset=+1]

include::toolkit-library-actions.adoc[leveloffset=+1]

include::toolkit-library-configure.adoc[leveloffset=+1]

include::toolkit-library-configure-ca.adoc[leveloffset=+1]

include::toolkit-library-configure-messages.adoc[leveloffset=+1]

include::toolkit-library-examples.adoc[leveloffset=+1]
