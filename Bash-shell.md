# Git Commands Reference  

This file contains a collection of Git commands that I have learned so far.  

## Table of Contents

1. [GitHub Authentication](#github-authentication)
2. [Create Public Repo](#create-public-repo)
3. [Set Remote Origin](#set-remote-origin)
4. [Rename Branch to Main](#rename-branch-to-main)
5. [Create a File](#create-a-file)
6. [Edit a File](#edit-a-file)
7. [Check Git Status](#check-git-status)
8. [Delete a File](#delete-a-file)
9. [View Repo in Browser](#view-repo-in-browser)



---
## GitHub Authentication

```bash
gh auth login
```

## Create Public Repo  

```bash 
gh repo create bash --public --confirm
```

## Set Remote Origin
```bash
git remote set-url origin https://github.com/pn1027/bah.git
```

## Rename branch to main
```bash
git branch -m master main
```

## Create a file
```bash
touch filename.ext
```

## Edit a file
```bash
code filename.ext
or 
nano filename.ext
```

## Check git status
```bash
git status
```

## Delete a file 
```bash
rm -r filename.ext
```
## View Repo in Browser
```bash
gh repo view --web
```
