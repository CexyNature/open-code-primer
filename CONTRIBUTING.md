# Contribution Guidelines

The purpose of this guide is to set clear expectations and mechanisms of contribution for everyone interested on improve this repository and book. These are mostly guidelines, not rules, so use your best judgement when contributing. By following these guidelines we hope we can ensure a positive experience for everyone and successfully harness the power of our community.

## Code of Conduct

Principles and mechanisms described on [SORTEE's Code of Conduct](https://www.sortee.org/codeofconduct/#:~:text=SORTEE%20is%20dedicated%20to%20providing,event%20participants%20in%20any%20form.) are extended to the online community involve in the creation of this repository and book. Please review our Code of Conduct which it is in effect at all times.

## Roles and Mechanisms for contributing

- Asking question (via GitHub Issues)
- Report bugs, typos, inconsistencies, etc (via GitHub Issues)
- Fix bugs and typos (via GitHub Issues)
- Request new features or suggest content (via GitHub Issues)
- Create media for complementing content
- Writing and editing content (via GitHub contributions such as Pull Request and Issues)
- Translating content to other languages

## How this repository and book are updated

The preferred method of contributing new content or amending existing content is via a GitHub Pull Request (PR). Every time a PR is accepted by the repository maintainers a GitHub workflow will run automatically performing three actions:

1. Updating the code base including the new content
2. Adding the author of the Pull Request to the list of contributors
3. Publishing updated repository to the hosting server (currently GitHub pages)

This automated process seeks to reduce the load on repository maintainers. Contributors can use the content of this book for preparing their contributions.

### Contributing to the code base

This repository uses `pre-commit`, a framework for managing and running Git hooks. Git hooks are scripts that run automatically during certain Git events (e.g., before a commit). Pre-commit ensures that code adheres to specific quality and formatting standards before being committed to the repository. Pre-commit hooks are defined in the file `.pre-commit-config.yaml`.

When contributing please ensure to install `pre-commit` packages and run `pre-commit install`. This command installs the hooks defined in `.pre-commit-config.yaml` file and sets up Git hooks to run them before each commit.

To manually run the hooks on all files in this repository, use:

```bash
pre-commit run --all-files
```

When our team updates the `.pre-commit-config.yaml` file, every active contributor must update their hooks by running:

```bash
pre-commit install --install-hooks
pre-commit autoupdate
```

## Policies on resolving conflict

To be developed.
