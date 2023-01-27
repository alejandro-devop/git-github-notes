# Chapter 6, Our first change
 Ok, time to add some content to our repository, start by creating an HTML file inside our repository, you can use your mouse by pressing right click and `Add new folder` or whatever is called in your operating system, or have fun and use the bash to do it:
 **Open your bash** and type the following command:

 _Linux / Mac / Windows Git bash / Windows PowerShell_
 ```bash
 touch index.html
 ```

 _Windows CMD_
 ```bash
 copy NUL index.html
 ```

This will create a file inside your repository, lets check the existance by typing the following command:

_Linux / Mac / Windows Git bash / Windows PowerShell_
```bash
ls -la
```
 You will see something like the following output

 _Output_
```bash
drwxr-xr-x   4 user  staff  128 Jan 26 18:34 .
drwxr-xr-x  18 user  staff  576 Jan 26 18:33 ..
drwxr-xr-x   9 user  staff  288 Jan 26 18:33 .git
-rw-r--r--   1 user  staff    0 Jan 26 18:34 index.html
```

The above is a list of the files in the current folder, the `.git` folder is another indicator that we are located in a git repository, Don't worry, the folder is hidden and is used only for git to store information about the repository.

> **Note** In windows the command to list files, is `dir`, no matter Uppercase or Lowercase.

Now, open the file and, you can use a [text editor](https://www.g2.com/categories/text-editor) or the bash to modify the file, just add the following content:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  <h1>My first page</h1>
</body>
</html>
```

## Checking if there is any change in my repository

We just added a new file to our project and this is considered a change, but how do we know is there any change in our repository? 

To know this we got the command `git status`, this command will show us if there is any change (something new, something changed, or something was removed) on our repository

**Open your bash** and run the following command
```bash
git status
```
_Output_

![image](https://user-images.githubusercontent.com/68975668/214976154-7e6e3aac-1b53-4011-9445-37d6e994ebf7.png)

You will be able to see under the label `Untracked files:` that there is a file colored in red, our brand new index.html file, untracked means that for git the file has no history, for git the file is brand new (Which is true). we will see more about the different status in further chapters

---
[Go to chapter 7](https://github.com/alejandro-devop/git-github-notes/blob/main/7-chapter/notes.md)