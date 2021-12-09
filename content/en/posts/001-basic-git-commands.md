---
title: "Basic Git commands"
date: 2021-09-30
description: "Notes when I am learning git commands."
draft: false
tags:
  - Git
---

### Git objects:
| object | description                    |
|--------|--------------------------------|
| blob   | text (codes)                   |
| tree   | file structures and file names |
| commit | commit message                 |

**HEAD**  indicated the current branch you are working at.

useful commands:
```sh
# creating branch based on your current HEAD branch
$ git branch <new-branch-name>


# create branch with specific version
$ git branch <new-branch-name> <version-SHA1-number>


# switching branch using "checkout" or "switch"
$ git checkout <other-branch-name>
$ git switch <other-branch-name>


# renaming branch based on your current HEAD branch
$ git branch -m <new-name>


# renaming specific branch
$ git branch -m <old-branch-name> <new-branch-name>


# print current status
$ git status


# print all branch, * indicate the branch you current on
$ git branch


# renaming a remote branch
# First: delete the current / old branch
$ git push origin --delete <old-name>
# Then simply push the new local branch with the current name
$ git push -u origin <new-name>


# Publish a branch, uploading a local branch for the first time
$ git push -u origin <local-branch>


# Track an remote branch locally with example
$ git branch --track feature/login origin/feature/login
-or-
$ git checkout --track origin/<base-branch>
```

 **References:**  
[Git Tutorial](https://reurl.cc/Q69aVq)  
[Git Branches Tutorial](https://reurl.cc/xEGX8e)  
[Git cheat sheet from Github](https://education.github.com/git-cheat-sheet-education.pdf)  
[Git cheat sheet from Git Tower](https://www.git-tower.com/learn/cheat-sheets/git-branches/)

