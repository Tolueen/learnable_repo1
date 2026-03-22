# learnable Writeup
## 1. Explain version control.
---
Version control, also known as source control, is the practice of tracking and managing changes to software code. Version control systems are software tools that help software teams manage changes to source code over time. As development environments have accelerated, version control systems help software teams work faster and smarter.

Version control software keeps track of every modification to the code in a special kind of database. If a mistake is made, developers can turn back the clock and compare earlier versions of the code to help fix the mistake while minimizing disruption to all team members.

For most software teams, the source code is a repository of invaluable knowledge and understanding about the problem domain that the developers have collected and refined through careful effort. Version control protects source code from both catastrophe and the casual degradation of human error and unintended consequences.
---

## 2. Explain difference between git and github
---
Git is a distributed version control system used to track and manage code changes locally while GitHub is a web-based platform that hosts Git repositories and provides collaboration features.

Git is primarily used through a command-line interface while Github provides a web-based graphical interface.

Git is installed locally on a developer’s system while github is hosted on the web.

Git is Focuses on version control and change tracking while GitHub Focuses on code hosting and collaboration.

Git Manages source code history while GitHub Hosts version-controlled repositories.
---

## 3. List 3 other github alternatives
*GitLab
*Bitbucket
*SourceForge

## 4. Explain the difference between git fetch and git pull
---
Git Fetch command is used to fetch all changes from the remote repository to the local repository. It doesn't make any changes to the current working directory. It stores all the changes in a separate branch called the remote-tracking branch while Git Pull command is used to fetch all changes from the remote repository to the current working directory. 
---

## 5. Explain in simple terms git rebase and the command for it
---
Git rebase is used to move your changes on top of the latest version of another branch.
The command for it is git rebase main.
---

***How it works***
---
It takes your changes and move them. It therfore places them on top of the latest main branch

## 6. Explain in simple terms git cherry-pick and the command for it 
---
Git cherry-pick lets you take a specific commit from one branch and apply it to another branch.
The command for it is ```git cherry-pick <commit-hash>

***How it works***
---
It finds the commit and copies the changes. Then it applies theem to my current branch as a new commit
