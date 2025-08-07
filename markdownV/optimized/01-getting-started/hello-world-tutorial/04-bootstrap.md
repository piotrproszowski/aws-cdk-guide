[#hello-world-bootstrap]
== Step 3: Bootstrap your \{aws} environment

In this step, you bootstrap the \{aws} environment that you configured in the previous step. This prepares your environment for CDK deployments.

To bootstrap your environment, run the following from the root of your CDK project:

== [source,bash,subs="verbatim,attributes"]

$ cdk bootstrap
---

By bootstrapping from the root of your CDK project, you don't have to provide any additional information. The CDK  CLI obtains environment information from your project. When you bootstrap outside of a CDK project, you must provide environment information with the `cdk bootstrap` command. For more information, see xref:bootstrapping-env[Bootstrap your environment for use with the \{aws} CDK].

