<img src="src/sortee-logo.png" alt="Thumbnail for Society for Open, Reliable, and Transparent Ecology and Evolutionary Biology" width="300"/>

# SORTEE's Open Code Primer

[![Automatic Release](https://github.com/CexyNature/open-code-primer/actions/workflows/release.yaml/badge.svg?branch=main&event=release)](https://github.com/CexyNature/open-code-primer/actions/workflows/release.yaml)

## Motivation

Biologists and ecologists face unique challenges when striving to adopt open coding practices. These obstacles highlight the need for a clear, structured, and community-driven Code Primer to empower researchers and foster best practices. Key challenges include:

- Navigating Standards:

The field lacks unified standards, or alternatively, offers an overwhelming variety of conflicting guidelines. This creates confusion about which practices to adopt.

- Balance Between Specificity and Generality:

Step-by-step guides are often too narrowly tailored, making them irrelevant to diverse projects, while broad guidance can lack the actionable detail researchers need.

- Data and Code Integration:

Eco-evolutionary research involves datasets ranging from large, standardized databases to highly ad-hoc, small datasets. Each presents unique challenges in storage, formatting, and linking to the code that processes them.

- Overwhelming Documentation:

Government datasets, though valuable, often come with excessive and complex documentation, making them difficult to navigate effectively.

- Data Sensitivity:

Ensuring appropriate handling of sensitive data remains a significant hurdle for open coding and data sharing.

- Streamlined Best Practices:

Researchers often struggle to balance simplicity with rigor, desiring workflows that are streamlined yet adhere to proper best practices without overwhelming users.

- Lack of Training:

Many biologists and ecologists lack formal training in coding and data analysis, leaving them unprepared to tackle modern computational challenges.

- Fostering Healthy Debate:

The field needs to revive a culture of constructive scientific debate. Fear of criticism or appearing negative can stifle the exchange of ideas crucial for refining methodologies and driving innovation.

By addressing these challenges, a Code Primer can serve as a bridge, offering actionable, accessible, and well-rounded guidance to researchers at all skill levels. It aims to streamline workflows, integrate best practices, and foster a collaborative, debate-driven scientific community.

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
