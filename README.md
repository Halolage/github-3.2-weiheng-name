# github-3.2-weiheng-name
Assignment for module 3.2

# Git Commands

This repository provides an overview of common Git commands and their usage.

## Table of Contents

- [Getting Started](#getting-started)
- [Basic Commands](#basic-commands)
- [Branching and Merging](#branching-and-merging)
- [Remote Repositories](#remote-repositories)
- [GitHub Authentication](#github-authentication)


## Getting Started

To get started with Git, you'll need to have it installed on your machine. You can download Git from the official website: [https://git-scm.com/](https://git-scm.com/).

## Basic Commands

### `git init`

Initialize a new Git repository in the current directory.

### `git clone <repository-url>`

Create a local copy of a remote repository.

### `git status`

Check the status of your repository, including modified files, untracked files, etc.

### `git add <file>`

Stage changes of a specific file for the next commit.

### `git commit -m "commit message"`

Commit the staged changes with a descriptive commit message.

### `git log`

View the commit history of the repository.

### `git diff`

Show the differences between the current state and the previous commit.

## Branching and Merging

### `git branch`

List all branches in the repository.

### `git branch <branch-name>`

Create a new branch with the specified name.

### `git checkout <branch-name>`

Switch to the specified branch.

### `git merge <branch-name>`

Merge changes from the specified branch into the current branch.

### `git rebase <branch-name>`

Reapply commits from the specified branch on top of the current branch.

## Remote Repositories

### `git remote add <remote-name> <repository-url>`

Add a remote repository with the given name and URL.

### `git push <remote-name> <branch-name>`

Push local commits to a remote repository.

### `git pull <remote-name> <branch-name>`

Pull changes from a remote repository into the current branch.

### `git fetch <remote-name>`

Fetch changes from a remote repository without merging.

## GitHub Authentication

GitHub authentication is the process of verifying the identity of users accessing a GitHub repository or interacting with GitHub services. It ensures that only authorized individuals can perform actions such as pushing code, creating issues, or commenting on pull requests.

GitHub provides several methods for authentication, allowing users to choose the one that best suits their needs:

**Username and Password:** The traditional method is to authenticate using a username and password. This method is suitable for individuals working with their own repositories or small teams.

__Personal Access Tokens:__ Personal access tokens (PATs) provide an alternative way to authenticate with GitHub. They are randomly generated tokens that can be used in place of a password. PATs offer more granular control over the permissions granted and can be used for automation or accessing the GitHub API.

__SSH Keys:__ Secure Shell (SSH) keys are a popular authentication method for developers. With SSH keys, you generate a public-private key pair and associate the public key with your GitHub account. This method offers secure and convenient access without the need to enter a password each time.

__OAuth Apps:__ OAuth (Open Authorization) is an industry-standard protocol for authorization. GitHub allows developers to create OAuth apps, which enable users to authenticate using their GitHub credentials while granting controlled access to their repositories or organization resources.

## Conclusion

This README provides an overview of common Git commands, their usage and overview of GitHub Authentication process and methods. Feel free to explore more advanced Git features and commands based on your specific needs.

For detailed information, refer to the official Git documentation: [https://git-scm.com/doc](https://git-scm.com/doc).

