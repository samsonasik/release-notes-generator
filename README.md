# Release Notes Generator

The way we generate release notes for Rector repository - https://github.com/rectorphp/rector/releases/

<br>

## Install

```bash
composer install rector/release-notes-generator --dev
```

## Usage

1. Generate Github token here: https://github.com/settings/tokens/new

2. Run the command:

```bash
GITHUB_TOKEN=<github_token> vendor/bin/rng --from-commit <from-commit-hash> --to-commit <to-commit-hash>
```
