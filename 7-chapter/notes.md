# Chapter 7, Confirm change (Commit)

Once we have all the modifications we want in our repository is time to confirm those changes (Create a commit), the confirmation of this changes will generate a restoration point for our repository, let's see how we can do this, first add the files we want to confirm as a change:

**Open your bash** and type the following command:
```bash
git add index.html
```
> **Note** Some commands don't give us a confirmation message, but trust me, it is ok.

Now run the git status command again:
```bash
git status
```
_output_

![image](https://user-images.githubusercontent.com/68975668/214981060-2cf742c9-ce43-4bfc-afea-93ee91a60f15.png)

Now you will see a new label `Changes to be commited:` and under this label you can se our file colored green, all green files are ready to be added to a new restoration point (commit).

To create a restoration point (commit) we use the command `git commit`, following by a message to describe or identify what is included in that restoration point. 

_**Open your bash** and type the following command:_

```bash
git commit -m "Added my first html file to my repository"
```
_output_

![image](https://user-images.githubusercontent.com/68975668/214981887-2dd4e176-83fe-43d2-9076-027b10d3fbaf.png)

This means our commit was a success.

---
[Go to chapter 8](https://github.com/alejandro-devop/git-github-notes/blob/main/8-chapter/notes.md)