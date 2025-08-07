# Deployment Guide

Everything you need to deploy AWS CDK applications to AWS environments.

## 🚀 Deployment Essentials

### Environment Setup
- [Bootstrapping](bootstrapping.md) - Prepare AWS environments for CDK
- [Bootstrap Environment](bootstrapping-env.md) - Environment-specific bootstrapping
- [Bootstrap Customizing](bootstrapping-customizing.md) - Custom bootstrap templates
- [Bootstrap Troubleshooting](bootstrapping-troubleshoot.md) - Common bootstrap issues

### Configuration and Access
- [Configure Access](configure-access.md) - Set up AWS credentials and permissions
- [Configure Environment](configure-env.md) - Environment configuration
- [Configure Synthesis](configure-synth.md) - Synthesis configuration options
- [SSO CLI Example](configure-access-sso-example-cli.md) - AWS SSO setup example

### Deployment Process
- [Deployment Chapter](chapter-deploy.md) - Overview of deployment process
- [CLI Reference](cli.md) - CDK CLI commands and options
- [Deploy Troubleshooting](deploy-troubleshoot.md) - Common deployment issues

### Permissions and Security
- [Permissions](permissions.md) - IAM permissions for CDK deployments
- [Usage Data](usage-data.md) - Understanding CDK usage metrics

## 🎯 Quick Start Deployment

### First-Time Setup
1. **[Configure Access](configure-access.md)** - Set up AWS credentials
2. **[Bootstrapping](bootstrapping.md)** - Prepare your AWS environment
3. **[CLI Usage](cli.md)** - Learn essential CDK CLI commands

### Environment-Specific Deployment
1. **[Configure Environment](configure-env.md)** - Set up multiple environments
2. **[Bootstrap Environment](bootstrapping-env.md)** - Bootstrap specific environments
3. **[Deployment Chapter](chapter-deploy.md)** - Deploy to different environments

### Troubleshooting
- **[Bootstrap Issues](bootstrapping-troubleshoot.md)** - Fix bootstrap problems
- **[Deploy Issues](deploy-troubleshoot.md)** - Resolve deployment failures

## 📋 Pre-Deployment Checklist

- [ ] AWS credentials configured
- [ ] Target environment bootstrapped
- [ ] Necessary permissions assigned
- [ ] Application tested locally
- [ ] CloudFormation templates synthesized

## 🔗 Related Sections

- [Getting Started](../01-getting-started/) - Initial setup
- [Development](../03-development/) - Prepare your application
- [Advanced](../05-advanced/) - Advanced deployment patterns