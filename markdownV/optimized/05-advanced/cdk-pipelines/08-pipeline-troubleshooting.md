[#cdk-pipeline-troubleshooting]
== Troubleshooting

The following issues are commonly encountered while getting started with CDK Pipelines.

_Pipeline: Internal Failure_::
+
---
CREATE_FAILED  | \{aws}::CodePipeline::Pipeline | Pipeline/Pipeline
Internal Failure
---
+
Check your GitHub access token. It might be missing, or might not have the permissions to access the repository.

_Key: Policy contains a statement with one or more invalid principals_::
+
---
CREATE_FAILED | \{aws}::KMS::Key | Pipeline/Pipeline/ArtifactsBucketEncryptionKey
Policy contains a statement with one or more invalid principals.
---
+
One of the target environments has not been bootstrapped with the new bootstrap stack. Make sure all your target environments are bootstrapped.

_Stack is in ROLLBACK_COMPLETE state and cannot be updated_::
+
---
Stack +++<STACK_NAME>+++is in ROLLBACK_COMPLETE state and cannot be updated. (Service: AmazonCloudFormation; Status Code: 400; Error Code: ValidationError; Request ID: \...) ---- + The stack failed its previous deployment and is in a non-retryable state. Delete the stack from the \{aws} CloudFormation console and retry the deployment.+++</STACK_NAME>+++
