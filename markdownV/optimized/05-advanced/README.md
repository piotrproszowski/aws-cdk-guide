# Advanced Topics

Advanced patterns, customizations, and enterprise features for AWS CDK.

## 🚀 Advanced Features

### CI/CD and Pipelines
- [CDK Pipelines](create-cdk-pipeline.md) - Continuous deployment ([detailed guide](cdk-pipelines/))
- [Stages](stages.md) - Multi-stage deployments
- [Blueprints](blueprints.md) - Reusable infrastructure patterns

### Customization and Extension
- [Customize Synthesis](customize-synth.md) - Custom synthesis behavior
- [Customize Permissions Boundaries](customize-permissions-boundaries.md) - IAM boundaries
- [Aspects](aspects.md) - Cross-cutting concerns and policies
- [Libraries](libraries.md) - Building and using CDK libraries

### CloudFormation Integration
- [CFN Layer](cfn-layer.md) - Low-level CloudFormation constructs
- [Use CFN Template](use-cfn-template.md) - Integrating existing CloudFormation
- [Use CFN Public Registry](use-cfn-public-registry.md) - Third-party resources

### Advanced Utilities
- [Get CloudFormation Values](get-cfn-val.md) - Retrieving CloudFormation outputs
- [Get Context Variables](get-context-var.md) - Working with context
- [Get Environment Variables](get-env-var.md) - Environment variable access
- [Get Secrets Manager Values](get-sm-val.md) - Secrets integration
- [Get SSM Parameter Values](get-ssm-val.md) - Parameter Store integration
- [Set CloudWatch Alarms](set-cw-alarm.md) - Monitoring and alerting

### Migration and Toolkit
- [Migration Guide](migrate.md) - Migrating from CDK v1 to v2
- [Toolkit Library](toolkit-library.md) - CDK Toolkit programmatic usage
- [Toolkit Actions](toolkit-library-actions.md) - Custom toolkit actions
- [Toolkit Configuration](toolkit-library-configure.md) - Toolkit customization
- [Toolkit Getting Started](toolkit-library-gs.md) - Toolkit library basics
- [Toolkit CA Configuration](toolkit-library-configure-ca.md) - CA certificates
- [Toolkit Messages](toolkit-library-configure-messages.md) - Custom messages

### Policy and Validation
- [Policy Validation](policy-validation-synthesis.md) - Policy validation during synthesis

## 🎯 Learning Paths

### CI/CD Pipeline Setup
1. **[CDK Pipelines](create-cdk-pipeline.md)** - Start with pipeline overview
2. **[Stages](stages.md)** - Understand deployment stages
3. **[Blueprints](blueprints.md)** - Use reusable patterns

### CloudFormation Integration
1. **[CFN Layer](cfn-layer.md)** - Low-level constructs
2. **[Use CFN Template](use-cfn-template.md)** - Template integration
3. **[Migration](migrate.md)** - Moving from CloudFormation

### Enterprise Features
1. **[Aspects](aspects.md)** - Policy enforcement
2. **[Customize Permissions](customize-permissions-boundaries.md)** - Security boundaries
3. **[Policy Validation](policy-validation-synthesis.md)** - Compliance checking

## 🔗 Related Sections

- [Core Concepts](../02-core-concepts/) - Foundation knowledge required
- [Development](../03-development/) - Development best practices
- [Deployment](../04-deployment/) - Basic deployment knowledge needed