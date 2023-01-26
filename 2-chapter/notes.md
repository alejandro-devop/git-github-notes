# Chapter 2, Some key concepts about git.

> **IMPORTANT** Through all the examples I'll be using [HTML](https://www.w3.org/), and I'll be assuming you understand a little bit of it, if you want to learn about HTML i recommend you to go [here](https://www.w3schools.com/html/)

---
Before to getting started with git material, there are some concepts that I considere are important for you to know:

## Bash
In software world we call [bash](https://en.wikipedia.org/wiki/Bash_(Unix_shell)), [terminal or command line](https://en.wikipedia.org/wiki/Command-line_interface) to a special application on our computer, this application allows us to give specific instructions to our computer, some of them the same instructions we can tell the computer using our mouse or keyboard.

_(Terminal in linux)_
![image](https://user-images.githubusercontent.com/68975668/214654668-6e78b310-db8e-4935-ab89-4c0efe066470.png)

_(CMD windows)_
![image](https://user-images.githubusercontent.com/68975668/214654881-5907dfdf-9933-401b-b078-cde87b127a44.png)

_(Terminal mac)_
![image](https://user-images.githubusercontent.com/68975668/214655057-e0040274-9e78-4d1c-b65c-432314bc0695.png)

---

## User or Username
As mentioned in the previous chapter the main purpose of Git is allow work in a collaborative way and for Git is important to know who made certain changes on a project. A **user** or **user name** is a special identificator (Which is just a word) used to differentiate your changes from those of other people within the project.

## Initialization
As mentioned in the previous chapter a project could be a bunch of files, an image, a word document or a lot of different types of digital files within a folder, the initialization is the process of telling **Git** that a folder will be considered a project. 

## Respositories
From now on we will call these projects initialized with **Git** as **Repositories**, the concept is the same from now on.

> **Note** any folder within your computer that has been initialized with **Git** is considered a repository, you can have multiple folders initialized  with **Git**, each one of them will be considered a different **Repository**.

## Changes
The word change is pretty self explanatory, we will call **change** to one or more modifications made to any file within a repository.

## Commit
As you work on a repository you could make a lot of changes, but this doesn't mean that these changes are being considered to be a part of the final result, probably you're just trying some things and see if they work. Unless you confirm that these changes will be a part of the final result you can always revert them (Delete them) and leave your project as it was before you start changing anything  (Like a restoring point), we will call these confirmed modifications as a **Commit**.

## History
As probably you're guessing right now, every time you confirm a change (Create a commit) **Git** creates a restoring point for your repository, yeah, every commit represents story or restoration point to your repository, we will call this list of commits as the History of your repository, because it works as a history line, from the beggining of the repository (initialization) to it's current state (last commit).

## Branches 
Branches are a concept that could be difficult to understand right now, but I want you to keep it in mind for now. Imagine that you need to modify your entire repository... you need to modify almost all files in your project, but even when you know you have restoration points with your commits, is safer to create a copy of your repository and work isolated on thise copy, this way you wont interfiere with others work and you can do anything you want, even create new restoration points (**commits**). But hold on, there is no need to copy and paste the entire folder, tools like **Git** allows you to do this, and **Git** call these copies **Branches** and we will see the reason for this name in the future.

---

[Go to chapter 3](https://github.com/alejandro-devop/git-github-notes/blob/main/3-chapter/notes.md)