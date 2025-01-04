# **Task Manager Tool**

This is a simple Python-based task management tool designed to help manage daily tasks efficiently. This project demonstrates a foundational Git workflow, including repository setup, branching, merging, conflict resolution, and syncing with a remote repository.

---

## **Setup Instructions**

### **1. Cloning the Repository**
To get started, clone the repository to your local machine:

```bash
git clone https://github.com/mykoooo/task-manager-tool.git
cd task-manager-tool
```

### **2. Git Configuration**
Ensure your Git configuration is set up correctly by running the following commands:

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
These commands will configure your Git username and email for commit history.
```

### **3. Basic Git Commands**
**a. Viewing Commit History**
To view the commit history in a concise format:

```bash
git log --oneline
```
**b. Creating and Switching Branches***
To create a new branch and switch to it:

```bash
git checkout -b <branch-name>
```

**c. Adding and Committing Changes**
After making changes, use the following commands to stage and commit them:


```bash
git add .
git commit -m "Your commit message"
```

**d. Merging Branches**
Switch back to the master branch and merge changes from your feature branch:

```bash
git checkout master
git merge <branch-name>
```
If there are any merge conflicts, resolve them manually by editing the files, then add and commit the resolved changes:

```bash
git add .
git commit -m "Resolved merge conflict"
```

**e. Pushing and Pulling Changes**
To push your changes to the remote repository:

```bash
git push origin <branch-name>
```

To pull updates from the remote repository:

```bash
git pull origin master
```

---

# Branching Strategy
1. feature/task-list branch
This branch added a basic task list feature, including a function to add tasks (add_task).

2. feature/print-tasks branch
This branch added a function to print the tasks (print_tasks).

Both branches were merged into the master branch. A merge conflict occurred during the second merge, which was manually resolved by keeping both functions.
