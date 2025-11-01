# Contributing to Ensemble Examples

Thank you for your interest in contributing examples! This guide will help you get started.

## Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/ensemble-edge/examples.git
   cd examples
   ```

2. **Explore existing examples**
   Browse the repository to understand the structure and patterns

3. **Create your example**
   Follow the structure guidelines below

## Example Structure

Each example should be self-contained and follow this structure:

```
example-name/
├── README.md           # Clear explanation of what it demonstrates
├── package.json        # Dependencies (if applicable)
├── .edgit/            # Edgit configuration
│   └── components.json
├── src/               # Source code
└── tests/             # Tests (optional but encouraged)
```

### README Requirements

Every example needs a comprehensive README with:

- **Title**: Clear, descriptive name
- **Description**: What this example demonstrates
- **Prerequisites**: Required tools, accounts, API keys
- **Setup**: Step-by-step installation instructions
- **Usage**: How to run the example
- **Key Concepts**: What you'll learn
- **Related**: Links to relevant documentation

## Submitting an Example

1. **Create a branch**
   ```bash
   git checkout -b examples/your-example-name
   ```

2. **Add your example**
   - Create a new directory
   - Add all necessary files
   - Include comprehensive README
   - Test thoroughly

3. **Commit your changes**
   ```bash
   git add examples/your-example-name
   git commit -m "docs(examples): add your-example-name"
   ```

4. **Push and create PR**
   ```bash
   git push origin examples/your-example-name
   ```

## Code of Conduct

This project follows the [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you agree to uphold this code.

## Trademark

Ensemble® is a registered trademark of Higinio O. Maycotte.
