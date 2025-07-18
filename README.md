# My First Git Project
<!-- git_test_project -->
Setup

| Command                                           | Purpose                     |
| ------------------------------------------------- | --------------------------- |
| `git config --global user.name "Your Name"`       | Set your Git username       |
| `git config --global user.email "your@email.com"` | Set your Git email          |
| `git --version`                                   | Check installed Git version |

project Initialization

| Command                | Purpose                                 |
| ---------------------- | --------------------------------------- |
| `git init`             | Initialize a Git repo in current folder |
| `git clone <repo-url>` | Clone (download) a repo from GitHub     |


Staging and commiting 

| Command                   | Purpose                             |
| ------------------------- | ----------------------------------- |
| `git status`              | See file changes and staging status |
| `git add <file>`          | Stage a specific file               |
| `git add .`               | Stage all changes                   |
| `git commit -m "Message"` | Save changes with a message         |

Remote Repository

| Command                       | Purpose                          |
| ----------------------------- | -------------------------------- |
| `git remote add origin <url>` | Connect local repo to GitHub     |
| `git remote -v`               | View current remotes             |
| `git push -u origin main`     | Push code to GitHub (first time) |
| `git push`                    | Push changes to GitHub           |
| `git pull`                    | Get latest changes from GitHub   |


Branching 

| Command                  | Purpose                           |
| ------------------------ | --------------------------------- |
| `git branch`             | List branches                     |
| `git branch <name>`      | Create a new branch               |
| `git checkout <name>`    | Switch to a branch                |
| `git checkout -b <name>` | Create and switch to a branch     |
| `git merge <branch>`     | Merge another branch into current |


Viewing History

| Command    | Purpose                           |
| ---------- | --------------------------------- |
| `git log`  | View commit history               |
| `git diff` | View code differences             |
| `git show` | Show details of a specific commit |


Undoing Mistakes

| Command              | Purpose                                     |
| -------------------- | ------------------------------------------- |
| `git restore <file>` | Undo changes in file (before commit)        |
| `git reset <file>`   | Unstage a staged file                       |
| `git reset --hard`   | Undo all uncommitted changes (⚠️ Dangerous) |


Git hub via SSH

| Command                                     | Purpose                           |
| ------------------------------------------- | --------------------------------- |
| `ssh-keygen -t ed25519 -C "your@email.com"` | Generate SSH key                  |
| `cat ~/.ssh/id_ed25519.pub`                 | View public key to copy to GitHub |


After Modifying the README.md file : 

| **Step** | **Command**                         | **Purpose**                                                   |
| -------- | ----------------------------------- | ------------------------------------------------------------- |
| 1️⃣      | `git status`                        | Check what has changed (you should see `modified: README.md`) |
| 2️⃣      | `git add README.md`                 | Stage the modified file for commit                            |
| 3️⃣      | `git commit -m "Changed README.md"` | Save the changes locally with a message                       |
| 4️⃣      | `git push`                          | Push (upload) your changes to the GitHub repository           |

