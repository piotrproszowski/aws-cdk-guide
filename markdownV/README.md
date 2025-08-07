# MarkdownV - AWS CDK Guide Documentation

This folder contains the AWS CDK Developer Guide documentation in Markdown format, available in two versions:

## 📚 Optimized Version (Recommended)

**👉 [Access Optimized Guide](optimized/README.md)**

The optimized version reorganizes content for better learning and GitHub Spaces compatibility:

### Key Improvements
- **Logical organization** by learning progression (Getting Started → Core Concepts → Development → Deployment → Advanced → Examples → Reference)
- **Smaller file sizes** - Large files split into focused sections (e.g., tokens guide, CDK pipelines tutorial)
- **Better navigation** - Clear folder structure with README guides for each section
- **GitHub Spaces compatible** - Optimized for space limitations while preserving all content

### Structure Overview
```
optimized/
├── 01-getting-started/     # New user onboarding
├── 02-core-concepts/       # Fundamental concepts  
├── 03-development/         # Development best practices
├── 04-deployment/          # Deployment and CI/CD
├── 05-advanced/           # Advanced patterns
├── 06-examples/           # Tutorials and examples
└── 07-reference/          # CLI reference and troubleshooting
```

## 📄 Original Version

**[Original Structure](v2/README.md)** - Contains 114 markdown files converted from AsciiDoc format

### Original Details
- **Source**: `v2/guide/*.adoc` files from the original repository
- **Tool Used**: kramdown-asciidoc (kramdoc) v2.1.0  
- **Total Files**: 114 markdown files
- **Structure**: Maintains original flat file organization

## 🚀 Quick Start

**For new users**: Start with the [Optimized Guide](optimized/README.md) for the best learning experience.

**For reference**: Use the [Original Structure](v2/guide/) to find specific files by their original names.

## 📊 Optimization Benefits

- **Size**: Original 1.6MB → Organized into logical sections
- **Files**: 114 → 151 (includes helpful navigation and split content)
- **Largest files reduced**: tokens.md (56KB → split into 8 focused files), create-cdk-pipeline.md (56KB → split into tutorial sections)
- **Navigation**: Added README guides and clear learning paths