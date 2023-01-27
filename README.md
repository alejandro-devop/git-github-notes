# Welcome to my notes about git

I love writing my notes as if I was speaking to someone else, if you're reading this I hope you receive it as if I am talking to you. Ahead I'll leave you an index about what you can find on my notes:

1. **[Chapter 1](https://github.com/alejandro-devop/git-github-notes/blob/main/1-chapter/notes.md)**, What is git and what need it solves.
2. **[Chapter 2](https://github.com/alejandro-devop/git-github-notes/blob/main/2-chapter/notes.md)**, Some key concepts about git.
3. **[Chapter 3](https://github.com/alejandro-devop/git-github-notes/blob/main/3-chapter/notes.md)**, Installation
4. **[Chapter 4](https://github.com/alejandro-devop/git-github-notes/blob/main/4-chapter/notes.md)**, First steps
5. **[Chapter 5](https://github.com/alejandro-devop/git-github-notes/blob/main/5-chapter/notes.md)**, Initialize a repository.
6. **[Chapter 6](https://github.com/alejandro-devop/git-github-notes/blob/main/6-chapter/notes.md)**, Our first change
7. **[Chapter 7](https://github.com/alejandro-devop/git-github-notes/blob/main/7-chapter/notes.md)**, Confirm change (Commit)
8. **[Chapter 8](https://github.com/alejandro-devop/git-github-notes/blob/main/8-chapter/notes.md)**, Check the history
9. _to be defined..._

--- 
# Git command cheat-sheet

> **IMPORTANT** If you are using windows I highly recommend you to use power shell and enable the [Windows Linux Subsystem](https://learn.microsoft.com/en-us/windows/wsl/install), with this you can use **All platform commands** without any problem.

## Git commands
In programming we call a cheat sheet as a list of usefull commands of instructions that usually get repetitive.

| Command | Name | Description |
| :------ | :--- | :--------- |
|  `git config --global user.email "[my-email]"`  |  Set email  | Tell git what is my user name |
|  `git config --global user.name "[my full name]"`  |  Set full name  | Tell git what is my human name |
|  `git init --initial-branch=main`  |  Initialize  |  Initializes a repository where the initial branch will be named `main`  |
|  `git init`  |  Initialize  |  Initializes a repository using `master` as initial branch  |
|  `git status`  |  Show status  |  Shows the current repository status  |
|  `git add [file-name]`  |  Add  |  Adds files to be confirmed as change (commit)  |
|  `git add .`  |  Add all  |  Add all files marked as `untracked`, `modified`, `deleted` to be confirmed as a change (Commit)  |
|  `git commit -m "[A message for my restoration point]"`  |  Create commit  |  Creates a restoration point for your project  |
|  `git commit -am "[A message]"`  |  Create commint and Add all  |  Add all modified, new, delete files to the current commit confirmation and creates a commit  |
|  `git log`  |  Show history  |  Shows you the current repository history  |
|  `git branch`  |  Show branches  |  Show the current created branches and shows  the current branch marked in the list  |
|  `git branch --show`  | Show my curren branch   |  Shows your current branch  |
|  `git branch [branch-name]`  |  Create branch  |  Create a new branch with the given name  |
|  `git branch -d [branch-name]`  |  Remove branch  |  Removes a branch with the given name, careful, the branch to remove cannot the active branch  |
|  `git branch -a`  |  View all branches  |  List all the branches, including the remote branches  |
|  `git checkout [branch-name]`  |  Switch to branch  |  Allows to jump to a branch with the given name  |
|  `git checkout -b [branch-name]`  |  Switch and create  |  Allows to jump to a branch with the given name, but, if the branch does not exists it creates it  |
|  `git checkout -`  |  Switch previous  |  Allows jump to the previous active branch  |
|  `git remote add origin [origin-url]`  |  Add remote origin  |  Allows to connect your current repository to a remote origin  |
|  `git remote remove origin`  |  Remove remote origin  |  Allows to remove the origin from you current repository  |
|  `git push -u origin [branch-name]`  |  Push branch by first time  |  Allows to push all your commits to the remote respository  |
|  `git push origin [branch-name]`  |  Push to remote  |  Same as previous but after first time  |
|  `git push`  |  Push all  |  Push any change of any branch (be careful with this one)  |
|  `git push -f origin [branch-name]`  |  Push forced  |  **CAREFUL**, it literally force your push and makes the remote repository exact as your local.  |
|  `git pull origin [branch-name]`  |  Get changes (pull changes)  |  It brings all changes that are in the remote repository but are not on your local  |
|  `git pull`  |  Pull all  |  Tries to bring all changes in the remote repository and syncronize them with your local repository  |

## All platform commands
| Command | Name | Description | Usage |
| :------ | :--- | :--------- | :------ |
|  `cd`  |  **Change dir**  |  Allows you to navigate through folders  | `cd /home/user/desktop`
|  `mkdir`  |  **Make directory**  |  Create a new folder  | `mkdir my-new-folder` |
|  `ls`  |  **List directory content**  |  Shows all content in the current directory  | `ls` |
|  `ls -la`  |  **List directory content vertical**  |  Shows the current directory content but in vertical format, also includes the hidden files  | `ls -la` |
|  `pwd`  | **Print working directory** | Shows the current directory path | `pwd` |
|  `clear` | **Clear** | Clear the current bash content | `clear` |
|  `touch [file-name].[extension]` | **Create file** | Creates a file in the current directory | `touch index.html`|


## Windows usefull commands
| Command | Name | Description | Usage |
| :------ | :--- | :--------- | :----- |
|  `dir`  | **Directory**   |  Shows all content in the current directory  |  |
|  `md`  |  **Make directory**  |  Creates a directory  | `md my_folder` |
|  `cls` |  **Clear screen**  |  Clear the current bash content | `cls` |
|  `copy NUL [file-name].[extension]` | **Create file** | Creates a file in the current directory | `copy NUL index.html` |


