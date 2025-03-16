# miniProject1_WebD
# Git & GitHub - Complete Guide

## 📌 Introduction
This miniProject provides a complete understanding of Git and GitHub, covering basic to advanced commands. It helps developers manage and track code efficiently using version control.

## 📖 What is Git?
- Git is a **distributed version control system** that tracks code changes and enables multiple developers to collaborate seamlessly.
- It maintains a history of changes, allowing easy rollback to previous versions.
- Without Git, changes need to be manually saved and shared, making collaboration difficult.

## ☁️ What is GitHub?
- GitHub is a cloud-based repository hosting service for Git projects.
- **Git** manages version control locally, while **GitHub** stores repositories remotely.

## 🔧 Installation & Setup
### Step 1: Install Git
- **Windows:** [Download Git]
- **Mac:** `brew install git`
- **Linux:** `sudo apt install git`

### Step 2: Configure Git
```sh
 git config --global user.name "Your GitHub Username"
 git config --global user.email "your-email@example.com"
```
Check Configuration:
```sh
git config --list
```

## 🛠️ Basic Git Commands
| Command | Description |
|---------|-------------|
| `git init` | Initialize a new Git repository |
| `git status` | Check repository status |
| `git add filename` | Add a specific file to the staging area |
| `git add .` | Add all files to staging |
| `git commit -m "message"` | Save changes with a commit message |
| `git branch branch-name` | Create a new branch |
| `git checkout branch-name` | Switch to another branch |
| `git merge branch-name` | Merge a branch into the main branch |
| `git push -u origin main` | Upload code to GitHub |
| `git pull origin main` | Fetch and update local repository |

## 🚀 Advanced Git Commands
| Command | Description |
|---------|-------------|
| `git log --oneline` | View commit history in one line |
| `git reset --hard HEAD~1` | Undo last commit |
| `git stash` | Save uncommitted changes temporarily |
| `git stash pop` | Retrieve stashed changes |
| `git rebase main` | Clean up and integrate commits |
| `git cherry-pick commit-id` | Apply a specific commit |
| `git tag -a v1.0 -m "Version 1.0"` | Mark a version |
| `git revert commit-id` | Undo a commit without deleting history |
| `git diff` | Compare changes before committing |
| `git clean -f` | Remove untracked files |

## 🎯 Real-Life Use Case
- A team developing a website uses Git branches for feature development.
- Members push changes to GitHub for review.
- The team leader merges changes into the main branch.
- If an issue arises, they restore the previous version effortlessly.

## 🔗 Resources
- [Official GitHub Documentation](https://docs.github.com/en)
- [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)

## 👨‍💻 Developer
**Abhishek Kumar**  
📩 Reach me on:  
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white)](https:/instagram.com/abhishek_7o1)  
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white)](https://github.com/abhishek23gecv)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhishek-kumar-050577268/)  

© 2025 All Rights Reserved.
