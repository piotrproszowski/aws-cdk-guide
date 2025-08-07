[#tokens-list]
== Working with list-encoded tokens

List-encoded tokens look like the following:

== [source,none,subs="verbatim,attributes"]

["#{TOKEN[Stack.NotificationArns.1234]}"]
---

The only safe thing to do with these lists is pass them directly to other constructs. Tokens in string list form cannot be concatenated, nor can an element be taken from the token. The only safe way to manipulate them is by using \{aws} CloudFormation intrinsic functions like  https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/intrinsic-function-reference-select.html[`Fn.select`].

