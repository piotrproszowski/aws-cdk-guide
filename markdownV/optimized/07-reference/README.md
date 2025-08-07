# Reference and Troubleshooting

Reference materials, troubleshooting guides, and additional resources for AWS CDK.

## 📖 Reference Materials

### CLI Reference
- [CLI Commands - Acknowledge](ref-cli-cmd-ack.md) - `cdk acknowledge` command
- [CLI Commands - Bootstrap](ref-cli-cmd-bootstrap.md) - `cdk bootstrap` command
- [CLI Commands - Context](ref-cli-cmd-context.md) - `cdk context` command
- [CLI Commands - Deploy](ref-cli-cmd-deploy.md) - `cdk deploy` command
- [CLI Commands - Destroy](ref-cli-cmd-destroy.md) - `cdk destroy` command
- [CLI Commands - Diff](ref-cli-cmd-diff.md) - `cdk diff` command
- [CLI Commands - Doctor](ref-cli-cmd-doctor.md) - `cdk doctor` command
- [CLI Commands - Import](ref-cli-cmd-import.md) - `cdk import` command
- [CLI Commands - Init](ref-cli-cmd-init.md) - `cdk init` command
- [CLI Commands - List](ref-cli-cmd-list.md) - `cdk list` command
- [CLI Commands - Logs](ref-cli-cmd-logs.md) - `cdk logs` command
- [CLI Commands - Metadata](ref-cli-cmd-metadata.md) - `cdk metadata` command
- [CLI Commands - Migrate](ref-cli-cmd-migrate.md) - `cdk migrate` command
- [CLI Commands - Notices](ref-cli-cmd-notices.md) - `cdk notices` command
- [CLI Commands - Synthesize](ref-cli-cmd-synth.md) - `cdk synth` command
- [CLI Commands - Version](ref-cli-cmd-version.md) - `cdk version` command
- [CLI Commands - Watch](ref-cli-cmd-watch.md) - `cdk watch` command

### Resource References
- [Resources](resources.md) - Comprehensive resource documentation

### How-To Guides
- [How-Tos](how-tos.md) - Common tasks and solutions

## 🔧 Troubleshooting

### General Troubleshooting
- [Troubleshooting Bootstrap](troubleshoot-bootstrap.md) - Bootstrap issues
- [Troubleshooting Deploy](troubleshoot-deploy.md) - Deployment problems
- [Troubleshooting Guide](troubleshooting.md) - General troubleshooting

## 🔒 Security and Compliance

### Security Reference
- [Security Overview](security.md) - CDK security considerations
- [IAM Security](security-iam.md) - IAM best practices
- [Infrastructure Security](infrastructure-security.md) - Infrastructure protection
- [Compliance Validation](compliance-validation.md) - Compliance frameworks
- [Disaster Recovery](disaster-recovery-resiliency.md) - DR and resiliency
- [Define IAM L2](define-iam-l2.md) - Level 2 IAM constructs

## 📋 Meta Information

### Documentation
- [Documentation History](doc-history.md) - Change history
- [PGP Keys](pgp-keys.md) - Verification keys

### Node.js
- [Node Versions](node-versions.md) - Supported Node.js versions

## 🎯 Quick Reference

### Common CLI Commands
```bash
cdk init app --language typescript  # Create new app
cdk bootstrap                       # Bootstrap environment  
cdk synth                          # Synthesize CloudFormation
cdk deploy                         # Deploy stack
cdk destroy                        # Delete stack
cdk diff                           # Show differences
```

### Troubleshooting Checklist
- [ ] CDK CLI version compatibility
- [ ] AWS credentials configured
- [ ] Environment bootstrapped
- [ ] Permissions sufficient
- [ ] Dependencies up to date

## 🔗 Related Sections

- [CLI Usage](../04-deployment/cli.md) - Detailed CLI guide
- [Getting Started](../01-getting-started/) - Initial setup
- [Development](../03-development/) - Development best practices