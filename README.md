# git-and-github-guide
A beginner-friendly guide to Git and GitHub with commands and examples.

# 📘 Git & GitHub Commands for Beginners

Welcome to your Git and GitHub learning journey! 🚀  
This guide is designed to help beginners understand and use Git and GitHub effectively. It includes essential commands, simple explanations, and pro tips to get you started with version control and collaboration.

---

## 📦 1. Git Setup

| Command | Description |
|--------|-------------|
| `git --version` | Check if Git is installed and see the version |
| `git config --global user.name "Your Name"` | Set your Git username |
| `git config --global user.email "you@example.com"` | Set your Git email |
| `git config --list` | View your Git configuration settings |

---

## 🛠️ 2. Starting a Git Project

| Command | Description |
|--------|-------------|
| `git init` | Start a new Git repository in your current folder |
| `git clone <repo-url>` | Copy a GitHub repository to your local machine |

---

## 📂 3. Tracking Changes

| Command | Description |
|--------|-------------|
| `git status` | See which files are changed or staged |
| `git add <filename>` | Stage a specific file for commit |
| `git add .` | Stage all changed files |
| `git commit -m "Your message"` | Save your changes with a message |
| `git log` | View the history of commits |

---

## 🌿 4. Working with Branches

| Command | Description |
|--------|-------------|
| `git branch` | List all branches |
| `git branch <branch-name>` | Create a new branch |
| `git checkout <branch-name>` | Switch to another branch |
| `git checkout -b <branch-name>` | Create and switch to a new branch |
| `git merge <branch-name>` | Merge another branch into your current branch |

---

## ⏪ 5. Undoing Changes

| Command | Description |
|--------|-------------|
| `git restore <filename>` | Undo changes in a file (before staging) |
| `git reset <filename>` | Unstage a file |
| `git reset --hard` | Undo all changes and reset to last commit (⚠️ use with caution) |

---

## ☁️ 6. Pushing to GitHub

| Command | Description |
|--------|-------------|
| `git remote add origin <repo-url>` | Connect your local repo to GitHub |
| `git push -u origin main` | Push your code to GitHub (first time) |
| `git push` | Push new commits to GitHub |
| `git pull` | Pull the latest changes from GitHub |

---

## 🤝 7. Collaboration

| Command | Description |
|--------|-------------|
| `git fork` | (On GitHub) Copy someone else's repo to your account |
| `git pull origin main` | Get the latest changes from the main branch |
| `git fetch` | Download changes without merging |
| `git merge` | Combine changes from another branch |

---

## 🔍 8. Viewing and Comparing Changes

| Command | Description |
|--------|-------------|
| `git show` | Show details of the latest commit |
| `git show <commit-id>` | Show details of a specific commit |
| `git diff` | Show changes not yet staged |
| `git diff <branch1> <branch2>` | Compare two branches |
| `git log --oneline` | View commit history in a compact format |
| `git log --graph --all --decorate` | Visualize branch history as a graph |

---

## 🏷️ 9. Tagging Versions

| Command | Description |
|--------|-------------|
| `git tag` | List all tags |
| `git tag <tag-name>` | Create a new tag (e.g., v1.0) |
| `git tag -a <tag-name> -m "message"` | Create an annotated tag |
| `git push origin <tag-name>` | Push a tag to GitHub |
| `git push origin --tags` | Push all tags to GitHub |

---

## 🌐 10. Working with Remotes

| Command | Description |
|--------|-------------|
| `git remote -v` | View connected remote repositories |
| `git remote add origin <url>` | Add a remote repository |
| `git remote remove origin` | Remove a remote connection |
| `git remote rename origin upstream` | Rename a remote |

---

## 🧹 11. Cleaning Up

| Command | Description |
|--------|-------------|
| `git clean -n` | Preview files that would be deleted |
| `git clean -f` | Delete untracked files (⚠️ use with caution) |
| `git gc` | Clean up unnecessary files and optimize the repo |

---

## ⚡ 12. Git Aliases (Shortcuts)

You can create shortcuts for long commands:

```bash
git config --global alias.st status
git config --global alias.co checkout
git config --global alias.br branch
git config --global alias.cm "commit -m"