# Contributing to NERV Theme

Thanks for your interest in contributing to NERV! This document outlines how to contribute to the project.

## Reporting Issues

If you find a bug or have a suggestion:

1. Check if the issue already exists
2. If not, open a new issue with:
   - A clear title
   - Steps to reproduce (for bugs)
   - Screenshots if relevant
   - Your editor and version

## Adding Support for New Editors

We welcome ports to additional editors! Here's how:

1. Create a new directory: `{editor}-extension/`
2. Add the theme file(s) following that editor's conventions
3. Update the README with installation instructions
4. Submit a PR

### Color Reference

When porting, use these core colors:

| Role | Hex |
|------|-----|
| Background | `#0a1612` |
| Elevated Surface | `#0f1f1a` |
| Border | `#2a4a3d` |
| Foreground | `#8fb3a5` |
| Muted Text | `#5a7a6d` |
| Accent (Orange) | `#e85d04` |
| Accent Hover | `#f4820b` |
| Error | `#c92a2a` |
| Warning | `#d4a017` |
| Success/String | `#4a8c5c` |

### Syntax Colors

| Token | Hex |
|-------|-----|
| Comment | `#4a6a5d` |
| String | `#4a8c5c` |
| Number/Boolean | `#d4a017` |
| Keyword | `#e85d04` |
| Type/Class | `#3a7a8c` |
| Function | `#8a5a8a` |
| Variable | `#8fb3a5` |
| Property | `#c97a4a` |
| Constant | `#5a9a8c` |
| Operator | `#5a7a6d` |
| Bracket | `#8e8e93` |

## Code Style

- Keep JSON files formatted with 2-space indentation
- Use lowercase hex colors
- Follow existing naming conventions

## Pull Requests

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly in the target editor
5. Submit a PR with a clear description

## Questions?

Open an issue and we'll help you out!
