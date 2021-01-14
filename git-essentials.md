## Git config


### Create SSH key and set up connection to Github

https://git-scm.com/book/en/v2/Git-on-the-Server-Generating-Your-SSH-Public-Key

### Configure username and email addres

https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup

## Git Terminology


> Some of the contents of this file are copied from the following sources:  
> - https://git-scm.com/docs/gitglossary
> - https://www.atlassian.com/git/glossary/terminology


### Repository

A Git repository is a collection of files of a project, and all changes made to those files. In other words, it's the full history of the files of the project.

You can initialize a new git repository with the `git init` command.

### Branch

A "branch" is a line of development. 

The most recent commit on a branch is referred to as the tip of that branch. The tip of the branch is referenced by a branch head, 
which moves forward as additional development is done on the branch. 
A single Git repository can track an arbitrary number of branches, but your working tree is associated with just one of them (the "current" or "checked out" branch), and `HEAD` points to that branch.

### Staging area

Also known as **index**, it stores the local changes of your "working tree", which is just to say, it stores the **recent changes you have made** to the repository since the last commit.


### Commit 

A "commit" is the Git equivalent of "save". When you *commit* your changes with a *commit message*, you capture a snapshot of the current state of the project. The commit you have created represents the changes that you made to the project since the last commit.


## Commands

Initialize new repository:

```
git init
```


Clone an existing repository:

```
git clone url-of-the-remote-repository
```


Add a remote URL:

```
git remote add
```


Add all changes in the current directory to the staging area:

```
git add .
```

Add changes of a file to the staging area:

```
git add filename.py
```

Create a commit:

```
git commit -m 'write commit message here'
```

Push changes to the remote repository:

```
git push
```

Fetch changes from the remote repository and merge it into your local repository:
 
```
git pull
```


Fetch changes (but don't merge them):

```
git fetch
```

View the commit history:


```
git log
```

View the commit history, and show code changes as well:

```
git log -p
```


Create a new branch:

```
git branch name-of-the-new-branch
```


Switch to another branch:


```
git checkout name-of-the-branch
```
