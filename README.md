<img src="src/sortee-logo.png" alt="Thumbnail for Society for Open, Reliable, and Transparent Ecology and Evolutionary Biology" width="300"/>

# SORTEE's Open Code Primer

[![Automatic Release](https://github.com/CexyNature/open-code-primer/actions/workflows/release.yaml/badge.svg?branch=main&event=release)](https://github.com/CexyNature/open-code-primer/actions/workflows/release.yaml)

## Motivation

## Authors

## Contributors

<table>
<tr>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://github.com/CexyNature>
            <img src=https://avatars.githubusercontent.com/u/29750401?v=4 width="100;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=César Herrera/>
            <br />
            <sub style="font-size:14px"><b>César Herrera</b></sub>
        </a>
    </td>
</tr>
</table>

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
