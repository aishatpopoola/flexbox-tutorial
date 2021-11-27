# My Notes on Git and GitHub

## Steps Taken on starting out a project on Git and GitHub

- Initialize your project using git by:

```bash
git init
```

## To check the changes made locally we do:

```bash
git status
```

### Create a repository on GitHUb

go to github and add a new repository without a README or License file

### ADD All Changes made locally on git

To add a single file we do:

```bash
git add <file-name>
```

To add all files we do:

```bash
git add .
```

### Then we commit our changes

```bash
git commit -m"<title>: <commit-message>"
```

### Rename master branch to Main branch

```bash
git branch -M main
```

### Add remote origin

This helps connect local project to github repository

```bash
git remote add origin <repo-link>
```

### Then we push our local code to github

If we are making our first ever push in a particular branch we do

```bash
git push -u origin <branch-name>
```

If the push isn't our first ever push we use

```bash
git push origin
```

### To create a new branch
N.B before we create a new branch and checkout we must always pull our code in the current branch (i.e: `develop`) to our local project to keep it up to date using:

```bash
git pull origin
```

to create a new branch we do:

```bash
git checkout -b <branch-name>
```

### To checkout a branch we do

```bash
git checkout <branch-name>
```

### To see all the branches in a git projct

```bash
git branch
```