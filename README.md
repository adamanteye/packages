# Upstream Version Checker

Here is my [nvchecker](https://github.com/lilydjwg/nvchecker) configuration to track upstream updates.

The workflow runs daily through GitHub Actions. When new versions are detected, GitHub issues will be automatically created to notify maintainers.
Version updates are committed to the repository's `old.json` file, and error logs from failed checks will generate corresponding issues.
