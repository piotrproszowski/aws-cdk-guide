# AWS CDK Tokens

Tokens are placeholders for values that aren't known when defining constructs or synthesizing stacks. This content has been organized into focused sections for better learning.

## 📚 Complete Tokens Guide

The comprehensive tokens documentation has been split into manageable sections:

**👉 [Access the Complete Tokens Guide](tokens/README.md)**

## Quick Reference

- **What are tokens?** - Placeholders for unknown values at synthesis time
- **When to use tokens?** - For values determined at deployment (ARNs, IDs, etc.)
- **How they work?** - Resolved during CloudFormation deployment

## Learning Path

1. Start with [Tokens Introduction](tokens/01-tokens-introduction.md)
2. Review [Basic Examples](tokens/02-tokens-examples.md) 
3. Learn about [Passing Tokens](tokens/03-tokens-passing.md)
4. Understand [How Tokens Work](tokens/04-tokens-how-they-work.md)

For specific token types, jump directly to the relevant section in the [complete guide](tokens/README.md).

## Related Topics

- [Constructs](constructs.md) - How tokens work within constructs
- [Stacks](stacks.md) - Passing tokens between stacks
- [Apps](apps.md) - Token resolution at the app level