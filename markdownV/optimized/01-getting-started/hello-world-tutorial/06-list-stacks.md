[#hello-world-list]
== Step 5: List the CDK stacks in your app

At this point, you should have a CDK app containing a single CDK stack. To verify, use the CDK  CLI `cdk list` command to display your stacks. The output should display a single stack named `HelloCdkStack`:

== [source,bash,subs="verbatim,attributes"]

$ cdk list
HelloCdkStack
---

If you don't see this output, verify that you are in the correct working directory of your project and try again. If you still don't see your stack, repeat xref:hello-world-create[Step 1: Create your CDK project] and try again.

