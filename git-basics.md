![Github logo](GitHub-Mark-64px.png)

# Git Basics

---

## What is Git?

### Version Control System (VCS) for tracking changes to computer files

`git init` Initialize Local Git Repository

`git add <file>` Add file(s) to Index

`git` Check status of working tree

`git` Commit changes i Index

`git pull` Pull latest from remote Repository

`git push` Push to remote Repository

`git clone` Clone repository into a new directory

---

Install Git

[Git link](https://git-scm.com/)

[For Mac Install](https://git-scm.com/download/mac)

---

Open `Terminal`

type `git --version` or `-v`

`cd` in to an existing project folder or create a new one with `mkdir` and give it a **`folder_name`**.

Create a new file by typing `touch` **`name_of_file`**

`Example: touch index.html`

Type in some code in the new file and save it.

In Terminal we want to initialize it.

Type `git init`.

This creates a `.git` folder in the directory, but we can't see it.

Before you start add your name and email by typing
`git config --global user.name "You_Name"`

and another one for email.

`git config --global user.email "your@email.com"`

1. Add your file to the repository by typing `git add index.html`.

2. Type `git status` chanes to be committed will appear.

3. If you want to remove the file type `git rm --cached index.hmtl`.

4. Type `git status` and you'll noticed the file is untracked.

5. Type `git add * .html` and this will add any html files to the staging area.

6. To add every file type `git add .`

7. Type `git commit -m "type a comment of what is being committed to the repo"`.

8. How to use `.gitigmore file`. This is to add files and folders we want to ignore and not add to the repo.
   Type `touch .gitignore` in the folder your working in and open it. `Example: If you have a log.txt file in your project folder, type the name of file in the .gitigmore file and save.

---

## Branches

1. To create a new branch first make sure your commit all changes to the repo.

2. Type `git branch name_of_new_branch`
   Just creating a new branch doesn't change us to the branch. type `git status` and you'll notice you are still in the old branch.

3. To switch branch type `git checkout` **`name_of_branch`**
   make all your changes and commit them like normal.

4. To switch back to the master branch type `git checkout` **`master`**

5. When your ready to merge the new branch back in to the master branch type `git merge` **`name_of_the_new_branch`**. A message might appear asking why this change is necessary. Type in a message.

---

`git init` initialize local Git Repository.

Go into a folder and type `git init` creates a `.git` folder in project and is hidden by default.

`git add` will add file or files to the staging area and then will be ready to commit

`git add` adds files to staging and `git add .` add all files to staging

`* .html`

`git status` to see what you have in the staging area and ready for commit

[https://www.youtube.com/watch?v=SWYqp7iY_Tc](reference)
