# assignment1

## Getting Started

To set up the project, clone the repository and follow the installation instructions below.

## Installation

1. git init
Usage: git init [repository name]

We have to navigate to our project directory and type the command git init to initialize a Git repository for our local project folder. Git will create a hidden .git directory and use it for keeping its files organized in other subdirectories.

2. git add

Usage: git add [file(s) name]
This will add the specified file(s) into the Git repository, the staging area, where they are already being tracked by Git and now ready to be committed.

3. git commit

Usage: git commit -m "message"
This command records or snapshots files permanently in the version history. All the files, that are there in the directory right now, are being saved in the Git file system.

4. git status

Usage: git status
This command will show the modified status of an existing file and the file addition status of a new file, if any, that has to be committed.

5. git push

Usage: git push origin [branch name]
Suppose, we have made some changes in the file and want to push the changes to our remote repository on a particular branch. By using the command git push, the local repository's files can be synced with the remote repository on Github.

6. git clone

Usage: git clone [URL]
Suppose, we want to work on a file that is on a remote Github repository as another developer. We can work on this file by clicking on Clone or Download and copying the link and pasting it on the terminal with the git clone command. This will import the files of a project from the remote repository to our local system.



