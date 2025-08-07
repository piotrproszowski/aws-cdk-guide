# AWS CDK Guide - Optimized for Learning

This is an optimized version of the AWS CDK Developer Guide, reorganized into logical learning sections for better GitHub Spaces compatibility and improved learning experience.

## 📚 Learning Path

### 🚀 1. [Getting Started](01-getting-started/)
**Start here if you're new to AWS CDK**
- CDK installation and setup
- Hello World tutorial  
- Basic development workflow
- Language-specific guides

### 🧠 2. [Core Concepts](02-core-concepts/)
**Essential concepts you need to understand**
- Apps, Stacks, and Constructs
- Tokens and dynamic values
- Environments and configuration
- Multi-stack applications

### 🛠️ 3. [Development](03-development/)
**Best practices for building CDK applications**
- Testing strategies
- Asset management
- Security best practices
- Development workflow

### 🚀 4. [Deployment](04-deployment/)
**Deploy your applications to AWS**
- Environment bootstrapping
- CLI usage and configuration
- Permissions and access
- Troubleshooting deployments

### ⚡ 5. [Advanced Topics](05-advanced/)
**Advanced patterns and enterprise features**
- CDK Pipelines (CI/CD)
- Custom constructs and libraries
- CloudFormation integration
- Migration and customization

### 🎯 6. [Examples](06-examples/)
**Real-world examples and tutorials**
- Serverless applications
- Complete walkthroughs
- Best practice implementations

### 📖 7. [Reference](07-reference/)
**Reference materials and troubleshooting**
- CLI command reference
- Troubleshooting guides
- Security and compliance
- Additional resources

## 🎯 Quick Start Paths

### **Absolute Beginner**
1. [Getting Started → Installation](01-getting-started/getting-started.md)
2. [Getting Started → Hello World Tutorial](01-getting-started/hello-world.md)
3. [Core Concepts → Overview](02-core-concepts/core-concepts.md)

### **Ready to Build**
1. [Development → Best Practices](03-development/best-practices.md)
2. [Development → Testing](03-development/testing.md)
3. [Deployment → Bootstrapping](04-deployment/bootstrapping.md)

### **Enterprise/Production**
1. [Advanced → CDK Pipelines](05-advanced/create-cdk-pipeline.md)
2. [Advanced → Security](05-advanced/customize-permissions-boundaries.md)
3. [Reference → Security Guide](07-reference/security.md)

## 📊 Optimization Details

### Size Reduction
- **Original**: 114 files, ~1.6MB
- **Optimized**: Organized into logical sections with split large files
- **Largest files split**: tokens.md, create-cdk-pipeline.md, hello-world.md

### Structure Benefits
- **Logical grouping** by learning progression
- **Better navigation** with clear folder structure
- **Focused content** with smaller, topic-specific files
- **Cross-references** maintained between sections

### GitHub Spaces Compatibility
- Smaller individual files (most under 25KB)
- Organized folder structure
- Clear navigation with README files
- Maintained all original content

## 🔄 Original Content

The original content structure is preserved in the `../v2/guide/` folder. This optimized version reorganizes the same content for better learning and GitHub Spaces compatibility.

## 📝 Navigation Tips

- Each folder has a README.md with overview and learning path
- Large topics are split into subdirectories (e.g., `tokens/`, `cdk-pipelines/`)
- Cross-references point to related sections
- Use folder READMEs to understand the scope and find specific topics

## 🤝 Contributing

When updating content:
1. Maintain the logical organization
2. Update cross-references if moving content
3. Keep individual files focused and reasonably sized
4. Update relevant README files for navigation