# Git-version-control-task

## What is Version Control?

Version control is a system that helps track changes to files over time. It enables collaboration, prevents data loss, and allows you to revert to previous versions of your work.

## Difference Between Git and GitHub

- **Git**: A version control system that tracks changes in your codebase locally.
- **GitHub**: A web-based platform for hosting Git repositories, enabling collaboration and code sharing.

## GitHub Alternatives

1. GitLab
2. Bitbucket
3. SourceForge

## Git Fetch vs Git Pull

- **Git Fetch**: Downloads changes from a remote repository without merging them into your local branch.
- **Git Pull**: Downloads changes and merges them into your current branch in one step.

## Git Rebase

Rebasing is a way to integrate changes from one branch into another by moving the base of the branch. It rewrites commit history to create a linear sequence of commits.

Command:

```bash
git rebase <branch-name>

```

## Git Cherry-Pick

Git cherry-pick is a way to select a specific commit from one branch and apply it to another branch. It’s useful when you want to take a particular change or bug fix from one branch and apply it to another branch without merging all the changes from that branch.

- **Example**:

Imagine you're working on two branches: main and develop. You’ve made several changes in develop, but there's one specific change (commit) that you want to bring over to main without merging the entire branch. Instead of merging the whole branch, you can cherry-pick just that one commit.

Command:

```bash
git cherry-pick <commit-hash>


```
