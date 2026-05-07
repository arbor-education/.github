# AGENTS.md

## Repository overview

This is the `arbor-education/.github` repository, a GitHub "magic" repository that stores default organization-level configuration. It is **not** a product codebase.

Contents:
- `.github/CODEOWNERS` - Default code owners for all repos in the org (currently `@arbor-education/DevOps_Reviewers`)
- `.github/PULL_REQUEST_TEMPLATE.md` - Default PR template (references Jira tickets at `orchard.atlassian.net`)

## Cursor Cloud specific instructions

- There is no application code, no dependencies, no services, no tests, and no build step in this repository.
- The only tool needed is `git`. No package managers, runtimes, or databases are required.
- Changes to this repo affect all other repositories in the `arbor-education` GitHub organization that don't override these defaults.
- When editing the PR template, follow the existing format (Jira ticket links use `https://orchard.atlassian.net/browse/`).
- There is nothing to lint, test, build, or run. Validation is limited to reviewing file contents manually.
