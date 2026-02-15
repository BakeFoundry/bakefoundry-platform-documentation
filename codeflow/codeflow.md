# Introduction

This repository will be used as a template by all developers who will create python applications.


## Key Features

| Feature | Functionality | Tools |
| :--- | :--- | :--- |
| Secret Scanning | Scans code for hardcoded secrets, tokens, and keys to prevent credential leaks. | Gitleaks |
| Code Quality Check | Analyzes source code for stylistic errors, bugs, and programming standard violations. | Pylint, Flake8 |
| Vulnerability Check | Identifies known security vulnerabilities in application dependencies. | Snyk |
| AMI Baking | Automated creation of immutable Amazon Machine Images with pre-configured dependencies. | Packer |
| AMI Scanning | Scans the generated AMI for operating system and package vulnerabilities. | Amazon Inspector |

## Workflow Template Calls

Following core workflows will be called from this template.