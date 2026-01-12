# Contributing to n8n

Thank you for your interest in contributing to **n8n**! We welcome contributions of all kinds, including bug reports, feature requests, code improvements, and documentation updates.

## How to Contribute

### 1. Fork the Repository

Fork the [pointblank-club/n8n](https://github.com/pointblank-club/n8n) repository to your GitHub account.

### 2. Clone the Fork

```bash
git clone https://github.com/<your-username>/n8n.git
cd n8n
```

### 3. Set Upstream Remote

```bash
git remote add upstream https://github.com/pointblank-club/n8n.git
```

### 4. Create a Branch

Create a new branch for your feature or bugfix:

```bash
git checkout -b <your-branch-name>
```

### 5. Make Your Changes

- Make your code changes or update documentation.
- Follow existing code style and conventions.
- Write tests if adding or modifying functionality.

### 6. Commit Your Changes

Write clear, concise commit messages that explain your changes:

```bash
git add .
git commit -m "feat/scope: Short description of your change"
```

### 7. Sync with Upstream (if needed)

```bash
git fetch upstream
git rebase upstream/main
```

### 8. Push Changes to Your Fork

```bash
git push origin <your-branch-name>
```

### 9. Open a Pull Request

- Go to the [Pull Requests](https://github.com/pointblank-club/n8n/pulls) section in GitHub.
- Click "New Pull Request" and select your branch.
- Describe your changes, referencing any related issues.

## Code Style

- Follow the formatting enforced in the repository.
- Use clear, meaningful variable and function names.
- Write comments where necessary for clarity.

## Reporting Bugs

If you find a bug:

1. Search [existing issues](https://github.com/pointblank-club/n8n/issues) to see if it’s already reported.
2. If not, [open a new issue](https://github.com/pointblank-club/n8n/issues/new) with as much detail as possible:
   - Steps to reproduce
   - Expected and actual behavior
   - Screenshots, logs, or error messages

## Requesting Features

- Please [open a new issue](https://github.com/pointblank-club/n8n/issues/new) and use the template if available.
- Describe the feature and its use case clearly.

## Code of Conduct

Please be respectful and considerate. Review our [Code of Conduct](CODE_OF_CONDUCT.md) before contributing.

## Questions?

For any questions or help, please open a discussion or contact the maintainers.

Thank you for helping make **n8n** better!
