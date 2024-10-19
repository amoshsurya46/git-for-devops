
# Git Commands Cheat Sheet

This cheat sheet contains a list of commonly used Git commands for version control.

## Basic Git Commands

### 1. Set Up and Configuration
```bash
# Configure username and email for Git
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"

# Check the current configuration
git config --list
```

### 2. Initializing a Repository
```bash
# Initialize a new Git repository
git init
```

### 3. Cloning a Repository
```bash
# Clone a repository from a remote URL
git clone <repository_url>
```

## Working with Commits

### 4. Checking Status
```bash
# Check the status of the working directory and staging area
git status
```

### 5. Staging and Committing
```bash
# Add all changes to the staging area
git add .

# Add specific files to the staging area
git add <file_name>

# Commit staged changes with a message
git commit -m "Your commit message"
```

### 6. Viewing Commit History
```bash
# View the commit history
git log

# View a compact commit history
git log --oneline
```

## Branching and Merging

### 7. Working with Branches
```bash
# List all branches
git branch

# Create a new branch
git branch <branch_name>

# Switch to a different branch
git checkout <branch_name>

# Create and switch to a new branch
git checkout -b <branch_name>
```

### 8. Merging Branches
```bash
# Merge a branch into the current branch
git merge <branch_name>
```

### 9. Deleting a Branch
```bash
# Delete a local branch
git branch -d <branch_name>
```

## Remote Repositories

### 10. Adding and Fetching Remotes
```bash
# Add a remote repository
git remote add origin <repository_url>

# Fetch from a remote repository
git fetch origin
```

### 11. Pushing and Pulling
```bash
# Push local changes to a remote repository
git push origin <branch_name>

# Pull changes from a remote repository
git pull origin <branch_name>
```

## Stashing Changes

### 12. Stashing and Applying Changes
```bash
# Stash uncommitted changes
git stash

# Apply stashed changes
git stash apply
```

## Undoing Changes

### 13. Resetting and Reverting
```bash
# Unstage changes
git reset <file_name>

# Revert a commit
git revert <commit_hash>
```

## Additional Useful Commands

### 14. Git Diff
```bash
# Show changes between commits, branches, or files
git diff
```

### 15. Checking Logs and Graphs
```bash
# Display the commit log in a graph structure
git log --graph --oneline --all
```

---

### End of Git Commands Cheat Sheet
