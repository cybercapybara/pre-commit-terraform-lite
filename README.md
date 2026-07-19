# pre-commit-terraform-lite

> Sane Terraform pre-commit hooks, curated and installable in one line.

**Status:** 🚧 In development

## Overview

A curated, one-line-install bundle of pre-commit hooks for Terraform repositories.

## Features

- Provide a ready `.pre-commit-config.yaml` with fmt, validate, tflint, docs and trivy hooks
- Bootstrap script that installs pre-commit and required tool dependencies
- Pinned, tested versions that actually work together
- Opt-in heavier hooks documented separately
- Example repo showing the hooks in action

## Stack

Shell bootstrap, pre-commit framework, Terraform tooling.

## Usage

```bash
curl -fsSL https://raw.githubusercontent.com/moveeeax/pre-commit-terraform-lite/main/install.sh | sh
```

## License

MIT
