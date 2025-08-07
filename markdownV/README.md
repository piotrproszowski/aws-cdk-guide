# MarkdownV - Converted AWS CDK Guide Documentation

This folder contains the AWS CDK Developer Guide documentation converted from AsciiDoc (`.adoc`) format to Markdown (`.md`) format.

## Contents

- **v2/guide/**: Contains 114 converted markdown files from the original AsciiDoc documentation
  - All files maintain the same naming convention (e.g., `apps.adoc` → `apps.md`)
  - Original directory structure is preserved
  - Cross-references and formatting are maintained where possible

## Conversion Details

- **Source**: `v2/guide/*.adoc` files from the original repository
- **Tool Used**: kramdown-asciidoc (kramdoc) v2.1.0
- **Total Files**: 114 markdown files
- **Conversion Date**: $(date)

## Usage

These markdown files can be used as an alternative format for the AWS CDK documentation, making it easier to work with in markdown-compatible tools and platforms.

## File Structure

```
markdownV/
├── README.md (this file)
└── v2/
    └── guide/
        ├── apps.md
        ├── aspects.md
        ├── assets.md
        └── ... (111 more files)
```

## Notes

- The converted files maintain AsciiDoc-style formatting syntax where direct markdown equivalents don't exist
- Cross-references using `xref:` syntax are preserved from the original format
- Code blocks and examples are maintained in their original form
- Some AsciiDoc-specific attributes (like `{aws}` substitutions) are preserved as-is