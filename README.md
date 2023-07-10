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
- [4 Commonly Used Git commands in Project](#4-commonly-used-git-commands-in-project)


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

- **Username and Password:** The traditional method is to authenticate using a username and password. This method is suitable for individuals working with their own repositories or small teams.

- __Personal Access Tokens:__ Personal access tokens (PATs) provide an alternative way to authenticate with GitHub. They are randomly generated tokens that can be used in place of a password. PATs offer more granular control over the permissions granted and can be used for automation or accessing the GitHub API.

- __SSH Keys:__ Secure Shell (SSH) keys are a popular authentication method for developers. With SSH keys, you generate a public-private key pair and associate the public key with your GitHub account. This method offers secure and convenient access without the need to enter a password each time.

- __OAuth Apps:__ OAuth (Open Authorization) is an industry-standard protocol for authorization. GitHub allows developers to create OAuth apps, which enable users to authenticate using their GitHub credentials while granting controlled access to their repositories or organization resources.

## 4 Commonly Used Git commands in Project

- 1\. git clone [repository URL]: This command is used to clone a remote repository to your local machine. It is crucial at the start of a project when you need to set up your local development environment. Cloning allows you to have a local copy of the repository and enables you to make changes, commit them, and push them back to the remote repository.

- 2\. git pull: The git pull command fetches changes from a remote repository and merges them into your current branch. It's useful when working collaboratively with others or when you want to incorporate the latest changes made by other team members into your local branch. Regularly pulling ensures you have the most up-to-date code and helps prevent conflicts when merging changes.

- 3\. git add [file(s)] and git commit -m "Commit message": These two commands work together to stage changes and create commits. git add [file(s)] adds specific files or changes to the staging area, while git commit -m "Commit message" creates a new commit with the changes in the staging area. Commits are essential for tracking changes in your project's history, providing a way to revert or review code changes.

- 4\. git push: The git push command is used to upload your local commits to a remote repository. After making changes and committing them locally, pushing the changes to the remote repository allows others to access and review your code. It is crucial for collaboration and keeping the remote repository up to date with your changes.

By using these four commands—git clone, git pull, git add and git commit, and git push—you can effectively collaborate with team members, keep your local and remote repositories in sync, and maintain a well-documented history of changes in your project.

## Conclusion

This README provides an overview of common Git commands, their usage and overview of GitHub Authentication process and methods. Feel free to explore more advanced Git features and commands based on your specific needs.

For detailed information, refer to the official Git documentation: [https://git-scm.com/doc](https://git-scm.com/doc).

