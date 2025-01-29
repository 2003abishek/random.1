```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
# Git Guide

## Introduction
Git is a version control system used to track changes in code. This guide provides basic commands to help you get started with Git.

## Installing Git
Download and install Git from the official website:
[Git Downloads](https://git-scm.com/downloads)

## Basic Git Commands

### 1. Configure Git (Only needed once)
```md
```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```
```

### 2. Initialize a Repository
```md
```bash
git init
```
```
This initializes a new Git repository in your project folder.

### 3. Clone a Repository
```md
```bash
git clone https://github.com/user/repo.git
```
```
This copies an existing repository to your local machine.

### 4. Check Status
```md
```bash
git status
```
```
Displays changes made to the working directory.

### 5. Add Files to Staging Area
```md
```bash
git add filename  # Add a specific file
git add .         # Add all changed files
```
```

### 6. Commit Changes
```md
```bash
git commit -m "Your commit message"
```
```
Commits the staged changes with a message.

### 7. Push Changes to Remote Repository
```md
```bash
git push origin main
```
```
Pushes changes to the `main` branch on GitHub.

### 8. Pull Latest Changes
```md
```bash
git pull origin main
```
```
Fetches and merges changes from the remote repository.

### 9. Create and Switch Branches
```md
```bash
git branch new-branch     # Create a new branch
git checkout new-branch   # Switch to the new branch
git switch new-branch     # Alternative way to switch
```
```

### 10. Merge Branches
```md
```bash
git checkout main    # Switch to main branch
git merge new-branch # Merge new-branch into main
```
```

### 11. View Commit History
```md
```bash
git log --oneline --graph --decorate --all
```
```

### 12. Undo Changes
```md
```bash
git reset HEAD~1  # Undo the last commit
git checkout -- filename  # Discard changes in a file
```
```

## Conclusion
This guide covers the basic Git commands needed for version control. For more details, visit the [Git Documentation](https://git-scm.com/doc).

Happy coding! 🚀

