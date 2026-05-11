---
name: write-markdown
description: >-
  Create or modify Markdown documentation in this project following the project's style guide and conventions.
  Use this skill when the user needs to write or update documentation, ensuring adherence to project standards for Markdown formatting, structure, and content.
  **IMPORTANT**: This skill MUST be consulted BEFORE making any modifications to Markdown files.
license: MIT
compatibility: opencode
metadata:
  audience: developers
  workflow: documentation
---

# Write Markdown Skill

This skill provides instructions for creating or modifying Markdown documentation in this project according to the project's conventions.

## When to use this skill

Use this skill when:

- Creating new Markdown documentation files
- Modifying existing Markdown documentation
- Needing guidance on proper Markdown formatting and structure
- Wanting to ensure documentation follows project style guidelines
- Writing documentation for code, features, or processes

## Before modifying Markdown files

**CRITICAL**: ALWAYS consult this skill BEFORE making any modifications to Markdown files.

This ensures all Markdown changes follow project conventions and style guidelines.

## Markdown Style Guide

This project follows the CommonMark specification for Markdown formatting:

1. **Headings**: Use ATX headings (h1-h6) with # symbols instead of setext headings
2. **Code blocks**: Use fenced code blocks with language identifiers
3. **Lists**: Preserve existing bullet list markers
4. **Sentences**: Write one sentence per line outside of code blocks
5. **Formatting**: Follow the project's specific Markdown conventions
6. **Whitespace**: Never add trailing whitespace at the end of a line
7. **End of file**: Every file must end with a newline character

## Documentation Conventions

- All documentation should follow the project's existing structure and tone
- Use the appropriate heading levels (`#` for main titles, `##` for sections, etc.)
- Include language identifiers in all fenced code blocks
- Every line of prose text (outside code blocks) must contain exactly one sentence
- Every sentence of prose text (outside code blocks) must be on one line
- Follow the CommonMark specification for all Markdown elements
- Ensure all links are properly formatted and functional
- Use consistent terminology with existing documentation

## File Structure and Organization

- Documentation files should be placed in appropriate directories following the project structure
- Maintain consistency with existing documentation patterns
- Use descriptive file names that reflect the content
- Follow the same organizational principles as other documentation in the project

## Content Standards

- Be clear, concise, and accurate
- Use active voice when possible
- Include relevant examples and code snippets
- Reference existing documentation where appropriate
- Keep technical documentation up-to-date with code changes
- Ensure all commands and examples are tested and working
