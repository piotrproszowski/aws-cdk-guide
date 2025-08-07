[#hello-world-build]
== Step 4: Build your CDK app

In most programming environments, you build or compile code after making changes. This isn't necessary with the \{aws} CDK since the CDK CLI will automatically perform this step. However, you can still build manually when you want to catch syntax and type errors. The following is an example:

====
[role="tablist"]
TypeScript::
+
[source,bash,subs="verbatim,attributes"]
---
$ npm run build

____
hello-cdk@0.1.0 build
tsc
---
____

JavaScript::
No build step is necessary.

Python::
No build step is necessary.

Java::
+
[source,bash,subs="verbatim,attributes"]
---
$ mvn compile -q
---
+
Or press  `Control-B` in Eclipse (other Java IDEs may vary)

C#::
+
[source,bash,subs="verbatim,attributes"]
---
$ dotnet build src
---
+
Or press F6 in Visual Studio

Go::
+
[source,bash,subs="verbatim,attributes"]
---
$ go build
---
====

