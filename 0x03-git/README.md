![Git and Github](../images/git-&-github.jpg "Git and Gihub image")
# Git and GitHub

Building projects is one of the core parts of being a developer. And Git and GitHub are essential tools to use when building projects with others.

Git is opensource and it track changes via a distributed version control system. This means that Git can track the state of different versions of projects while developing them. It is distributed because it can access code files from another computer – and so can other developers.

When building an open source project, Git helps documenting or tracking code. This helps make work organized, and helps keep track of the changes made.

But also need a place to host code – which makes controlling each version of project easier and faster. This is where GitHub comes in.

GitHub is a "hub" (a place or platform) where Git users build software together. GitHub is also an hosting provider and version control platform you can use to collaborate on open source projects and share files. When using GitHub, Git is also working beneath the hood.

## Differences between Git and GitHub
![Git or Github](../images/Git-vs-GitHub.png "Git vs GitHub image")

|S.No|Git|GitHub|
|---|------------|------------|
|1.|Git is a software|GitHub is a service|
|2.|Git use Command line interface|GitHub use graphical user interface|
|3.|Git is maintained by Linux|GitHub is maintained by Microsoft|
|4.|Git is focused on version control to manage and share code|GitHub is focused on centralized source code hosting for Git|


## Using Git and GitHub

To start using Git and GitHub, there'are some certain things to do.

1. Install Git.
2. Create a GitHub Account.
3. Update GitHub account profile.
4. Create GitHub personal access token.
5. Create a respository on GitHub.
6. Clone respository on local machine.
7. Connect GitHub account with Git Account.
8. Create and edit code files locally.
9. Push local files to GitHub.

## Basic Git Commands

A Git command is a string of text that tells Git what to do. Each Git command does a different task, but they all work together to help developers manage their code changes.

Here are some common git commands:

**git init:** Initialize a new git repository. This is the first command you should run when starting a new project.

**git clone:**  Clone an existing git repository. This command allows you to create a local copy of a remote repository.
git add: Add files to a repository. This command allows you to add new files or changes to already existing files to a git repository.

**git commit:** Make changes to a repository. This command saves your changes to the git history.

**git push:** Push changes to a git remote repository. This command pushes your local commits to a remote git repository.

**git pull:** Pull changes from a git remote repository. This command pulls down any remote changes and incorporates them into your local git repository.

**git fetch:** To download contents from a remote repository.

**git status:** Check the status of your git repository. This will let you know which files have been modified and which files are being tracked by git.

**git log:** View the commit history for your git repository. This is useful for finding out when certain changes were made and who made them.
git reset:  Reset your git repository to a specific commit. This command allows you to undo changes to a file or reset your git history.

**git checkout:** Navigate between the branches created by git branch.

**git branch:**  Used to create a new branch. When you want to start a new feature, you create a new branch off main using `git branch new_branch` . Once created you can then use `git checkout new_branch` to switch to that branch.

**git reset:** Undo local changes to the state of a Git repo.

**git switch:** Help to switch to HEAD branch.

**git merge:** Combine multiple sequences of commits into one unified history. In the most frequent use cases, git merge is used to combine two branches.