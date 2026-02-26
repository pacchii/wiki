## 🔧 Git Setup & Common Commands

```bash
git init
git commit -m "First Commit"
git branch -M main
git remote add origin git@github.com:pacchdfsdsdfsdii/golang.git
git push -u origin main

git pull origin main --rebase
```



# 📘 Git Commands Cheat Sheet

---

## 🚀 Initial Setup

```bash
# Initialize a new repository
git init

# Add all files
git add .

# First commit
git commit -m "Initial commit"

# Rename branch to main
git branch -M main

# Add remote repository
git remote add origin <repo-url>

# Push to remote
git push -u origin main
```

---

## 🔄 Daily Workflow

```bash
# Check status
git status

# Add changes
git add .

# Commit changes
git commit -m "Your message"

# Pull latest changes (recommended: rebase)
git pull origin main --rebase

# Push changes
git push
```

---

## 🌿 Branching

```bash
# Create new branch
git branch feature-branch

# Switch branch
git checkout feature-branch

# Create and switch (shortcut)
git checkout -b feature-branch

# List branches
git branch

# Delete branch
git branch -d feature-branch
```

---

## 🔀 Merging

```bash
# Switch to main
git checkout main

# Merge feature branch
git merge feature-branch
```

---

## 🔁 Rebase

```bash
# Rebase current branch with main
git checkout feature-branch
git pull origin main --rebase
```

---

## 📦 Stashing

```bash
# Save changes temporarily
git stash

# List stashes
git stash list

# Apply stash
git stash apply

# Apply and remove stash
git stash pop
```

---

## 🔍 Logs & History

```bash
# Show commit history
git log

# One line log
git log --oneline

# Show changes
git diff
```

---

## ❌ Undo Changes

```bash
# Unstage file
git reset <file>

# Discard changes
git checkout -- <file>

# Undo last commit (keep changes)
git reset --soft HEAD~1

# Undo last commit (remove changes)
git reset --hard HEAD~1
```

---

## 🌐 Remote Repository

```bash
# Show remote
git remote -v

# Change remote URL
git remote set-url origin <new-url>

# Fetch changes
git fetch
```

---

## 🧹 Cleanup

```bash
# Remove untracked files
git clean -f

# Remove untracked directories
git clean -fd
```

---

## 🏷️ Tags

```bash
# Create tag
git tag v1.0

# Push tag
git push origin v1.0

# List tags
git tag
```

---

## 💡 Best Practices

- Always pull before pushing:
  ```bash
  git pull origin main --rebase
  ```

- Write meaningful commit messages  
- Use feature branches for development  
- Avoid committing directly to `main`  

---

## ⭐ Quick Summary

```bash
git add .
git commit -m "message"
git pull origin main --rebase
git push
```
