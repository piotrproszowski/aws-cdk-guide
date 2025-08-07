[#cdk-pipeline-protect]
=== Protecting your bootstrap stack from deletion

If a bootstrap stack is deleted, the \{aws} resources that were originally provisioned in the environment to support CDK deployments will also be deleted. This will cause the pipeline to stop working. If this happens, there is no general solution for recovery.

After your environment is bootstrapped, do not delete and recreate the environment's bootstrap stack. Instead, try to update the bootstrap stack to a new version by running the `cdk bootstrap` command again.

To protect against accidental deletion of your bootstrap stack, we recommend that you provide the `--termination-protection` option with the `cdk bootstrap` command to enable termination protection. You can enable termination protection on new or existing bootstrap stacks. To learn more about this option, see `xref:ref-cli-cmd-bootstrap-options-termination-protection[--termination-protection]`.

After enabling termination protection, you can use the \{aws} CLI or CloudFormation console to verify.

. Run the following command to enable termination protection on a new or existing bootstrap stack:
+
[source,none,subs="verbatim,attributes"]
---
$ cdk bootstrap --termination-protection
---
+
. Use the \{aws} CLI or CloudFormation console to verify. The following is an example, using the \{aws} CLI. If you modified your bootstrap stack name, replace `CDKToolkit` with your stack name:
+
[source,none,subs="verbatim,attributes"]
---
$ aws cloudformation describe-stacks --stack-name +++<CDKToolkit>+++--query "Stacks[0].EnableTerminationProtection" true ----+++</CDKToolkit>+++

