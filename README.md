# GitHub Composite Actions

A collection of reusable GitHub Composite Actions built from scratch to automate CI/CD workflows across multiple repositories. These actions are designed with production-ready practices, modularity, and reusability in mind.

## What You'll Find

This repository contains reusable Composite Actions for:

- Checkout source code
- Build applications
- Run Shell scripts
- Package artifacts
- Upload artifacts to Artifactory
- Download artifacts from Artifactory
- Deploy applications
- Execute pre/post deployment tasks
- Manage environment variables
- Validate inputs
- Security and quality checks
- Notification integrations
- Common CI/CD automation tasks

## Tech Stack

- GitHub Actions
- Composite Actions (`action.yml`)
- Bash / Shell Scripting
- Git
- JFrog Artifactory
- Linux

## Repository Structure

```text
.
├── checkout/
├── build/
├── upload-artifact/
├── download-artifact/
├── deploy/
├── notifications/
└── README.md
```

Each directory contains a reusable Composite Action that can be referenced from any GitHub Actions workflow.

## Goals

- Promote reusable CI/CD components
- Eliminate duplicate workflow logic
- Standardize automation across repositories
- Follow production-grade DevOps practices
- Improve maintainability and scalability

## Use Cases

- CI/CD pipeline automation
- Enterprise DevOps workflows
- Production deployments
- Multi-repository standardization
- Platform engineering
- Interview preparation and learning

## Contributions

Suggestions and improvements are welcome. Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
