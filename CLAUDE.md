# CLAUDE.md

This file provides guidance to Claude Code and other AI assistants when working with the Ensemble examples repository.

## Repository Purpose

This repository contains usage examples and templates for Ensemble products (Edgit and Conductor). Each example demonstrates specific features or use cases.

## Example Structure

Each example follows this structure:
```
example-name/
├── README.md           # Clear explanation and setup instructions
├── package.json        # Dependencies (if applicable)
├── .edgit/            # Edgit configuration (for edgit examples)
├── src/               # Source code
└── tests/             # Tests (optional)
```

## Git Commit Standards

### Commit Message Format
All commits must follow Conventional Commits format WITHOUT any AI attribution:

- **NEVER** append "code written by claude" or similar attribution to commit messages
- **NEVER** add signatures, author notes, or "written by" suffixes
- Use clean, professional commit messages focusing only on the changes

### Correct Format:
```
<type>(<scope>): <subject>

[optional body]
```

### Examples:
✅ CORRECT:
- `docs(examples): add basic edgit workflow example`
- `fix: correct installation instructions in README`
- `feat: add conductor workflow example`

❌ INCORRECT:
- `docs: add example - code written by claude`
- `feat: new example (written by Claude)`
- Any commit with AI attribution or signatures

### Commit Types:
- `docs:` - Documentation changes (most common for this repo)
- `feat:` - New example added
- `fix:` - Fix existing example
- `chore:` - Maintenance tasks

## Adding New Examples

1. Create example directory with descriptive name
2. Include comprehensive README with:
   - Description of what it demonstrates
   - Prerequisites
   - Setup instructions
   - Usage instructions
   - Key concepts
3. Test the example works as documented
4. Commit with conventional commit format (NO AI attribution)

## File Organization

- Keep examples self-contained
- Use clear, descriptive naming
- Include all necessary configuration files
- Document any prerequisites or setup steps

## Resources

- [Examples Contributing Guide](CONTRIBUTING.md)
- [Documentation](https://docs.ensemble.ai)
- [Edgit Documentation](https://docs.ensemble.ai/edgit)
- [Conductor Documentation](https://docs.ensemble.ai/conductor)
