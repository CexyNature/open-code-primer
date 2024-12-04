<img src="src/sortee-logo.png" alt="Thumbnail for Society for Open, Reliable, and Transparent Ecology and Evolutionary Biology" width="300"/>

# SORTEE's Open Code Primer

## Motivation

## Authors

## Contributors

## Contributing

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

## Inspiration

This repository was inspired by [Cookbook concept](https://cookbooks.projectpythia.org) from [Project Pythia](https://projectpythia.org).
