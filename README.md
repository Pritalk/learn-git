# Git Commands Cheatsheet

A handy reference for commonly used Git commands.

---

## **Basic Commands**

| Command                           | Description                                 |
|-----------------------------------|---------------------------------------------|
| `git init`                        | Initialize a new Git repository in a folder. |
| `git clone <repo-url>`            | Clone a repository to your local machine.   |
| `git status`                      | Show the current state of your repo (e.g., staged, modified files). |
| `git add <file>`                  | Add a file to the staging area.             |
| `git add .`                       | Add all files in the current directory to the staging area. |
| `git commit -m "message"`         | Save changes with a descriptive message.    |
| `git log`                         | View commit history.                        |

---

## **Branching**

| Command                           | Description                                 |
|-----------------------------------|---------------------------------------------|
| `git branch`                      | List all branches.                         |
| `git branch <branch-name>`        | Create a new branch.                       |
| `git checkout <branch-name>`      | Switch to a specific branch.               |
| `git checkout -b <branch-name>`   | Create and switch to a new branch.         |
| `git merge <branch-name>`         | Merge another branch into the current one. |

---

## **Remote Repositories**

| Command                           | Description                                 |
|-----------------------------------|---------------------------------------------|
| `git remote add origin <url>`     | Link your local repo to a remote repo.     |
| `git pull`                        | Fetch and merge changes from the remote repo. |
| `git push origin <branch-name>`   | Push changes to a specific branch on the remote repo. |
| `git fetch`                       | Download changes from the remote but don't merge them yet. |

---

## **Undo Changes**

| Command                           | Description                                 |
|-----------------------------------|---------------------------------------------|
| `git reset <file>`                | Unstage a file from the staging area.      |
| `git reset --hard <commit>`       | Reset to a specific commit and discard all changes after it. |
| `git checkout -- <file>`          | Discard changes in a file and restore the last committed version. |

---

## **Stashing**

| Command                           | Description                                 |
|-----------------------------------|---------------------------------------------|
| `git stash`                       | Save uncommitted changes for later.        |
| `git stash apply`                 | Reapply stashed changes.                   |
| `git stash list`                  | View all stashed changes.                  |

---

## **Tagging**

| Command                           | Description                                 |
|-----------------------------------|---------------------------------------------|
| `git tag <tag-name>`              | Create a tag for a specific commit.        |
| `git tag`                         | List all tags in the repository.           |
| `git push origin <tag-name>`      | Push a tag to the remote repository.       |

---

