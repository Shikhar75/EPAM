# Basic Git Workflow

## Introduction

A Git workflow is a sequence of steps used to track and save changes. Learning a few basic commands makes it easier to maintain a repository and publish learning notes.

## Important Concepts

### 1. Initialising a Repository

The `git init` command starts a new Git repository in the current folder.

```bash
git init
```

### 2. Checking the Repository Status

The `git status` command shows which files are new, modified, staged, or ready to be committed.

```bash
git status
```

### 3. Staging Changes

Staging means selecting the changes that should be included in the next commit.

```bash
git add README.md
```

To stage all changes in the current folder:

```bash
git add .
```

### 4. Saving a Commit

After staging, `git commit` saves the selected changes in the repository history.

```bash
git commit -m "Create learning portfolio"
```

### 5. Connecting to GitHub

A local repository can be connected to a remote GitHub repository. The remote is commonly named `origin`.

```bash
git remote add origin https://github.com/USERNAME/REPOSITORY.git
git push -u origin main
```

Replace the example URL with the URL of your own repository. The exact first-push steps can vary depending on how the GitHub repository was created.

## Practical Applications

- Saving updated Markdown notes.
- Checking which files have changed before committing.
- Uploading local changes to GitHub.
- Keeping a clear history of portfolio updates.

## My Understanding

A basic workflow is: make changes, check the status, stage the files, commit them, and push the commits to GitHub. This gives me a repeatable way to maintain my learning portfolio.

## Self-Assessment

1. What does `git init` do?
2. How is staging different from committing?
3. Which command shows the current status?
4. Why should commit messages be meaningful?
5. What does `git push` do?
