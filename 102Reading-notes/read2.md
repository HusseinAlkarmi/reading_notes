# INTRODUCTION

## Prerequisites
Before beginning this tutorial, it is highly recommended that you have a solid understanding of the Terminal (for Mac) or Command Line (for Windows and Linux).

In order to explain Git, we have to first explain various aspects of Version Control.

## Version Control
Version Control is a system that allows you to go back and forth between different versions of a file or set of files by keeping track of changes. Version control allows you to restore a file or project to a previous version, track and compare changes, and revert to a previous version. Mistakes in files can be quickly corrected with the help of a Version Control System (VCS).

## Types of Version Control
1. Local Version Control
2. Centralized Version Control
3. Distributed Version Control

## What is git?
Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.


## History of Git
Git traces its roots to the open source software project Linux kernel. Developers of this project began using a DVCS called BitKeeper in 2002. In 2005, many of these developers stopped using this DVCS due to tension between the Linux kernel community and the company behind BitKeeper’s and the eventual revocation of the DVCS’ gratis status. Subsequently, Linus Torvalds, the chief architect of the Linux kernel, began creating Git. With the intention of creating a DVCS with a workflow design similar to that of BitKeeper, which was also fast, Git allowed for non-linear development via multiple branches, could support large projects, possessed strong mechanisms preventing corruption, and had a simple design. Since its inception in 2005, Git has become one of the most utilized Version Control Systems in the world.

## How to Download Git
In order to use Git, your computer must have it available. If you already have Git on your computer, you should make sure you have the latest version.

Git can be installed in three ways:

1. Install as a package
2. Install via another installer
3. Download and compile the source code.

+ Mac OS X

Terminal

The simplest method for installing Git on a Mac (for Mavericks 10.9 and above) is running Git from the Terminal. If Git is not installed, you will see a prompt for installation.

Git Website

You can also download Git by visiting this link and following the posted directions: 

http://git-scm.com/download/mac

GitHub

A third option is to install Git as part of the GitHub for Mac install. GitHub is repository hosting service, which we will discuss in a future section.

Download GitHub for Mac via the following link:

http://mac.github.com

+ Windows
Git Website

You can download Git by visiting this link and following the posted directions:

http://git-scm.com/download/win

GitHub

Install Git as part of the GitHub for Windows install.

http://windows.github.com

+ Linux
Package Manager

You can try installing Git via your distribution’s inherent package management tool.

For Fedora:

$ sudo yum install git
For Ubuntu:

$ sudo apt-get install git
Git Website

To download Git for Linux, visit this link and follow the posted directions:

http://git-scm.com/download/linux

# Setting up a Git Repository

## Importing
To import an existing project or directory into Git, follow these steps using the Terminal or Command Line:

Switch to the target project’s directory
Example:

$ cd test (cd = change directory)
Use the git init command
$ git init
Note: At this stage, you have created a new subdirectory named .git that has the repository files. Tracking has not commenced.

To start tracking these repository files, perform an initial commit by typing the following:

$ git add *.c

$ git add LICENSE

$ git commit -m “any message here”

Now, your files are tracked and there’s an initial commit. We will discuss the particular commands in detail soon.

## Cloning
You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL:

$ git clone https://github.com/test

By cloning the file, you have copied all versions of all files for a project. This command leads to the creation of a directory called “test,” with an initialized .git directory inside it, which has copies of all versions of all files for the specified project. The command also automatically checks out — or retrieves for editing — a copy of the newest version of the project.

To clone a repository into a directory with another name of your choosing, use the following command format:

$ git clone https://github.com/test mydirectory
The command above makes a copy of the target repository in a directory named “mydirectory.”

# Workflow
* Local Repository Structure
The local Git repository has three components:

1. Working Directory: The actual files reside here.
2. Index: The area used for staging
3. Head: Points to the most recent commit
![image](https://blog.udemy.com/wp-content/uploads/2015/08/image036.png)

* Saving Changes
All files in a checked out (or working) copy of a project file are either in a tracked or untracked state.

Tracked

Tracked files can be modified, unmodified, or staged; they were part of the most recent file snapshot.

Untracked

Untracked files were not in the last snapshot and do not currently reside in the staging area.

*After cloning a repository, files have tracked status and are unmodified because they have been checked out but not edited.

* The Life Cycle of File Status
1. After you edit a file, Git flags it as modified because of changes made after the previous commit.
2. You stage the modified file.
3. Then, you commit staged changes.
![image](https://blog.udemy.com/wp-content/uploads/2015/08/image006.png)

* Check File Status
To determine the state of files, utilize the git status command:

$ git status
On branch master

nothing to commit, working directory clean

*This information indicates which branch you’re on (we will cover branches in a later section) and states “working directory clean,” which means that files have tracked or modified status at the moment. Also, no untracked files are present because Git has not listed any.

* Tracking and Staging a New File

**Single File**

Track one file only by using the following format:

git add filename

**All Files**

Track all files in a repository by using the following command:

$ git add *
*After using these commands, files are tracked and staged for committing.

After adding a new file called EXAMPLE, you would see information regarding changes to be committed when using the git status command:

$ git status

On branch master

Changes to be committed:

  (use "git reset HEAD ..." to unstage)
new file: EXAMPLE
This information tells us that there are changes to be committed and that the file has been staged.

* Committing a File

After staging one or multiple files, you should commit the changes and record what you did within the commit message:

$ git commit -m “made change x,y,z”
*This step has committed changes for the file or files (you can have one commit message for multiple files, if applicable) to the HEAD.

* Committing All Changes

$ git commit -a
*This command commits a snapshot of all modifications to tracked files in the working directory.

* Pushing Changes

Next, you would push changes to a remote repository. We will discuss remote repositories in more depth in the next section. For now, we will look at a general overview of pushing changes to remotes.

Example:

$ git push origin master
*This command pushes changes from the local “master” branch to the remote repository named “origin”.

*For cloned repositories, Git will automatically give the name “origin” to the server from which you cloned and the name “master” to your local repository. However, these names can be changed by the user.

# Remote Repositories

In order to collaborate on Git projects, you must interact with remote repositories, versions of a project residing online or on a network. You can work with multiple repositories, for which you can have read/write or read-only privileges. Teams can use remote repositories to push information to and pull data from.

+ Cloned Repositories

As mentioned earlier, for cloned repositories, Git will automatically give the name “origin” to the server from which you cloned and the name “master” to your local branch.