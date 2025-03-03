# 🚀 Git Commands Guide

This document provides a comprehensive guide to essential Git commands along with their explanations.

---

## 📌 **1. Check Git Version**
```sh
git --version
```
🔹 **Description:** Checks if Git is installed and displays the installed version.

---

## 📌 **2. Check Repository Status**
```sh
git status
```
🔹 **Description:** Shows the current state of the working directory and staging area.

---

## 📌 **3. Configure Git User Email**
```sh
git config --global user.email "your-email@example.com"
```
🔹 **Description:** Sets the global email address for Git commits.

---

## 📌 **4. Configure Git User Name**
```sh
git config --global user.name "your name"
```
🔹 **Description:** Sets the global username for Git commits.

---

## 📌 **5. List Git Configurations**
```sh
git config --list
```
🔹 **Description:** Displays all the Git configurations applied globally and locally.

---

## 📌 **6. Initialize a Git Repository**
```sh
git init
```
🔹 **Description:** Initializes a new Git repository in the current directory.

---

## 📌 **7. Git Workflow: Write ✍️ -> Add ➕ -> Commit ✅**
### **Steps to add and commit files:**
1️⃣ **Write**: Create or modify files.  
2️⃣ **Add**: Stage the files using `git add`.  
3️⃣ **Commit**: Save the changes with a message.

---

## 📌 **8. Add Specific Files to Staging**
```sh
git add <file1> <file2>
```
🔹 **Description:** Stages specific files to be committed.

---

## 📌 **9. Commit Changes**
```sh
git commit -m "write message"
```
🔹 **Description:** Saves the staged changes with a meaningful commit message.

---

## 📌 **10. View Commit History**
```sh
git log
```
🔹 **Description:** Displays the history of commits with details like author, date, and commit hash.

---

## 📌 **11. View Compact Commit History**
```sh
git log --oneline
```
🔹 **Description:** Shows a simplified commit history with only commit hashes and messages.

---

## 📌 **12. List All Branches**
```sh
git branch
```
🔹 **Description:** Displays all the branches in the repository.

---

## 📌 **13. Create a New Branch**
```sh
git branch <branch-name>
```
🔹 **Description:** Creates a new branch.

---

## 📌 **14. Switch to a Branch**
```sh
git switch <branch-name>
```
🔹 **Description:** Moves from the current branch to the specified branch.

---

## 📌 **15. Switch Back to Master/Main Branch**
```sh
git switch master
```
🔹 **Description:** Switches back to the `master` branch.

---

## 📌 **16. Create and Switch to a New Branch**
```sh
git switch -c <branch-name>
```
🔹 **Description:** Creates a new branch and switches to it.

---

## 📌 **17. Checkout a Specific Branch**
```sh
git checkout orange-mode
```
🔹 **Description:** Switches to the `orange-mode` branch (older method, `git switch` is preferred).

---

## 📌 **18. Checkout the Main Branch**
```sh
git checkout main
```
🔹 **Description:** Switches back to the `main` branch.

---

## 📌 **19. Merge a Branch**
```sh
git merge <branch-name>
```
🔹 **Description:** Merges the specified branch into the current branch.

---

## 📌 **20. Rebase a Branch**
```sh
git rebase <branch-name>
```
🔹 **Description:** Moves the base of the current branch onto another branch, integrating changes cleanly.

---

## 📌 **21. Cherry-pick a Commit**
```sh
git cherry-pick <commit-id>
```
🔹 **Description:** Applies a specific commit from another branch onto the current branch.

---

## 📝 **Assignment**
### 🔄 **Rename a Branch**
```sh
git branch -m <old-branch-name> <new-branch-name>
```
🔹 **Description:** Renames an existing branch.

---

### ❌ **Delete a Branch**
```sh
git branch -d <branch-name>
```
🔹 **Description:** Deletes the specified branch (if it's merged). Use `-D` to force delete an unmerged branch.

---

## 🎉 **Happy Coding!** 🚀
