# Chapter 5 Initialize a repository.

There are two ways to initialize a repository, from local and from remote (Github, but we well see this later). I'll do it from the local, your computer.

**Open your bash** and create a folder, you can name it as you want
```bash
mkdir my-first-repository
```
Now move (change directory) to the created folder
```bash
cd my-first-repository
```

To initialize a repository just type the following command:
```bash
git init --initial-branch=main
```

You can also just type, but for now I recommend you to use the previous command, it will help us when we start working with github.
```bash
git init
```
If you're using **Git bash** you will see something like this: 
![git bash](https://user-images.githubusercontent.com/68975668/214970441-6b8efeee-595f-4893-8ad7-9affd42f14d5.PNG)

After initializing the repository a word `main` or `master` surrounded by parenthesis will appear, this is an indicator that your repository has been initialized and now you can start adding some changes to it.

If you're using Mac or Linux you will need to install [Oh my zsh](https://ohmyz.sh/) for Mac and  [Oh my bash](https://github.com/ohmybash/oh-my-bash) for Linux, these are extensions for your terminal which will allow you to see the your repository as it is on **Git bash** for windows.

> **Note** In the commant `git init --initial-branch=main`  the part where it says `--initial-branch=main` is to indicate that the initial or main branch will be named  `'main'`,  no worries, you will learn more about branches in later chapters

[Go to chapter 6](https://github.com/alejandro-devop/git-github-notes/blob/main/6-chapter/notes.md)