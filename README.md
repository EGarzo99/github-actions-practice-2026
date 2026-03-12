# GitHub Actions Practice Repository

This repository contains a simple GitHub Actions workflow created
following the [GitHub Actions Quickstart guide](https://docs.github.com/en/actions/get-started/quickstart). The workflow
is defined in `.github/workflows/github-actions-demo.yml` and is
triggered on every push.

## Workflow details
- **Name:** GitHub Actions Demo
- **Trigger:** `push` event
- **Job:** `Explore-GitHub-Actions` running on `ubuntu-latest`
- **Steps:**
  1. Print information about the event, runner, branch, and repository.
  2. Checkout the repository using `actions/checkout@v5`.
  3. List the files in the workspace.
  4. Echo the job status.

Feel free to modify the workflow or add new ones as you explore
GitHub Actions.
