# Git & Linux Commands Cheat Sheet

A quick reference guide for essential Git and Linux commands used in software development and version control.

---

## Linux Commands

| Command | Description |
|--------|-------------|
| `ls` | Lists the files in the present working directory |
| `cd` | Changes directory |
| `mkdir` | Creates a new directory |
| `pwd` | Prints the present working directory |
| `touch` | Creates an empty file |

---

## Git Commands

| Command | Description |
|--------|-------------|
| `git init` | Initializes a new Git repository in your current directory |
| `git status` | Displays the current state of your working directory and staging area |
| `git add <file>` | Stages changes to a specific file |
| `git add .` | Stages all changes in the directory |
| `git commit -m "message"` | Records a snapshot of staged changes with a message |
| `git remote add origin <url>` | Connects your local repo to a remote one named “origin” |
| `git push origin <branch>` | Pushes commits to the specified branch on the remote |
| `git push origin main` | Pushes commits to the `main` branch on the remote |
| `git clone <url>` | Creates a local copy of a remote repository |
| `git pull` | Fetches and merges changes from the remote repository |
| `git branch` | Lists all branches in your repository |
| `git branch <name>` | Creates a new branch with the given name |

---

## Notes

- Use `git status` frequently to keep track of your changes.
- Always write meaningful commit messages.
- Use branches to isolate features or fixes before merging into `main`.

---



