# Basic Git Commands

This document provides a brief overview of basic Git commands with examples.

## 1. `git status`
This command displays the state of the working directory and the staging area. It lets you see which changes have been staged, which are in the working directory, and which files aren’t being tracked by Git.

```bash
$ git status
```

## 2. `git init`
This command is used to create a new Git repository. It can be run in an empty directory to start a new repository.

```bash
$ mkdir my-repo
$ cd my-repo
$ git init
```

## 3. `git clone`
This command is used to create a copy of an existing repository. You can clone a repository from a remote source using the URL.

```bash
$ git clone https://github.com/user/repo.git
```

## 4. `git add`
This command adds changes in your working directory to your staging area. This prepares your changes to be committed.

```bash
$ git add filename.txt    # Add a specific file
$ git add .               # Add all changes in the working directory
```

## 5. `git commit`
This command captures a snapshot of the currently staged changes and stores it in the repository’s history. It's essential to write a meaningful commit message.

```bash
$ git commit -m "Add new feature"
```

## 6. `git push`
This command is used to upload your local commits to a remote repository, pushing all changes to the specified branch.

```bash
$ git push origin main  # Push commits to the main branch
```

## 7. `git pull`
This command fetches changes from the remote repository and merges them into your local branch. This is the way to update your local repository with changes made by others.

```bash
$ git pull origin main  # Pull changes from the main branch
```

Remember to replace `main` with your branch name if you are working in a different branch.