# Version Control Basics

## What is Version Control?

Version control is a system that records changes in a file over time. It enables several users to work on a project and keeps a record of changes, which makes it easy to revert to an earlier version if necessary.

## Git vs GitHub

- **Git**: A distributed version control system to handle source code history Git is a command-line tool that you can install locally on your machine.
- **GitHub**: Its set of tools facilitates collaboration, issue management, and versioning.

## Alternatives to GitHub

1. GitLab
2. Bitbucket
3. SourceForge

## Git Fetch vs Git Pull

- **git fetch**: Downloads the latest updates from a remote repository but does not merge them with your local branch.
- **git pull**: Combines `git fetch` and a merge operation to update your local branch with changes from the remote repository.

## Git Rebase

- **Definition**: Rebase rewrites commit history by applying changes from one branch onto another, creating a cleaner history.
- **Command**:
  ```bash
  git rebase <branch-name>
  ```

## Git Cherry-Pick

- **Definition**: Cherry-pick allows you to select specific commits from one branch and apply them to another.
- **Command:**

```bash
git cherry-pick <commit-hash>
```
