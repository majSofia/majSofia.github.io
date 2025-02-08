# Linux & Git Basics Guide

A simple guide covering everyday Linux and Git commands.

---

## Linux Basics

### Navigating the Filesystem
```sh
# List files in a directory
ls -l

# Change directory
cd <directory>

# Go to home directory
cd ~

# Go up one directory level
cd ..
```

### File Operations
```sh
# Create a new file
touch <filename>

# Create a new directory
mkdir <directory>

# Copy a file
cp <source> <destination>

# Move or rename a file
mv <source> <destination>

# Delete a file
rm <filename>

# Delete a directory and its contents
rm -r <directory>
```

### Viewing and Editing Files
```sh
# View a file’s contents
cat <filename>
less <filename>

# Edit a file with nano
nano <filename>
```

### Process Management
```sh
# List running processes
ps aux

# Kill a process
kill <PID>

# Find a process by name
pgrep <process_name>
```

### Permissions
```sh
# Change file permissions
chmod 755 <filename>

# Change file ownership
chown user:group <filename>
```

### Package Management
#### Debian-based (Ubuntu, Debian)
```sh
# Update package lists
sudo apt update

# Install a package
sudo apt install <package>

# Remove a package
sudo apt remove <package>
```
#### Arch-based (Arch, Manjaro)
```sh
# Update package lists
sudo pacman -Syu

# Install a package
sudo pacman -S <package>

# Remove a package
sudo pacman -R <package>
```

---

## Git Basics

### Setting Up Git
```sh
# Configure your user information
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### Creating a Repository
```sh
# Initialize a new repository
git init
```

### Cloning a Repository
```sh
# Clone an existing repository
git clone <repository_url>
```

### Checking Repository Status
```sh
# Check for changes, staged files, and untracked files
git status
```

### Adding and Committing Changes
```sh
# Add a single file
git add <file>

# Add all changes
git add .

# Commit changes with a message
git commit -m "Your commit message"
```

### Pushing Changes
```sh
# Push changes to the remote repository
git push origin main
```

### Pulling Changes
```sh
# Pull the latest changes from the remote repository
git pull origin main
```

### Checking Commit History
```sh
# View commit history
git log --oneline --graph
```

### Creating and Switching Branches
```sh
# Create a new branch
git branch <branch_name>

# Switch to the new branch
git checkout <branch_name>

# Create and switch in one command
git checkout -b <branch_name>
```

### Merging Branches
```sh
# Merge a branch into the current branch
git merge <branch_name>
```

### Undoing Changes
```sh
# Undo changes to a file (before staging)
git checkout -- <file>

# Unstage a file
git reset HEAD <file>

# Revert a commit
git revert <commit_hash>
```

### Stashing Changes
```sh
# Save uncommitted changes temporarily
git stash

# Apply the last stashed changes
git stash pop
```

### Deleting a Branch
```sh
# Delete a local branch
git branch -d <branch_name>

# Delete a remote branch
git push origin --delete <branch_name>
```

### Helpful Shortcuts
```sh
# Set the default branch to main
git branch -M main

# Show remote repositories
git remote -v

# Show the last commit
git show --stat HEAD
```

---
This guide covers the basics of Linux and Git for daily use. For more, check out:
- [Linux Documentation](https://linuxcommand.org/)
- [Git Documentation](https://git-scm.com/doc)# Linux & Git Basics Guide

A simple guide covering everyday Linux and Git commands.

---

## Linux Basics

### Navigating the Filesystem
```sh
# List files in a directory
ls -l

# Change directory
cd <directory>

# Go to home directory
cd ~

# Go up one directory level
cd ..
```

### File Operations
```sh
# Create a new file
touch <filename>

# Create a new directory
mkdir <directory>

# Copy a file
cp <source> <destination>

# Move or rename a file
mv <source> <destination>

# Delete a file
rm <filename>

# Delete a directory and its contents
rm -r <directory>
```

### Viewing and Editing Files
```sh
# View a file’s contents
cat <filename>
less <filename>

# Edit a file with nano
nano <filename>
```

### Process Management
```sh
# List running processes
ps aux

# Kill a process
kill <PID>

# Find a process by name
pgrep <process_name>
```

### Permissions
```sh
# Change file permissions
chmod 755 <filename>

# Change file ownership
chown user:group <filename>
```

### Package Management
#### Debian-based (Ubuntu, Debian)
```sh
# Update package lists
sudo apt update

# Install a package
sudo apt install <package>

# Remove a package
sudo apt remove <package>
```
#### Arch-based (Arch, Manjaro)
```sh
# Update package lists
sudo pacman -Syu

# Install a package
sudo pacman -S <package>

# Remove a package
sudo pacman -R <package>
```

---

## Git Basics

### Setting Up Git
```sh
# Configure your user information
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### Creating a Repository
```sh
# Initialize a new repository
git init
```

### Cloning a Repository
```sh
# Clone an existing repository
git clone <repository_url>
```

### Checking Repository Status
```sh
# Check for changes, staged files, and untracked files
git status
```

### Adding and Committing Changes
```sh
# Add a single file
git add <file>

# Add all changes
git add .

# Commit changes with a message
git commit -m "Your commit message"
```

### Pushing Changes
```sh
# Push changes to the remote repository
git push origin main
```

### Pulling Changes
```sh
# Pull the latest changes from the remote repository
git pull origin main
```

### Checking Commit History
```sh
# View commit history
git log --oneline --graph
```

### Creating and Switching Branches
```sh
# Create a new branch
git branch <branch_name>

# Switch to the new branch
git checkout <branch_name>

# Create and switch in one command
git checkout -b <branch_name>
```

### Merging Branches
```sh
# Merge a branch into the current branch
git merge <branch_name>
```

### Undoing Changes
```sh
# Undo changes to a file (before staging)
git checkout -- <file>

# Unstage a file
git reset HEAD <file>

# Revert a commit
git revert <commit_hash>
```

### Stashing Changes
```sh
# Save uncommitted changes temporarily
git stash

# Apply the last stashed changes
git stash pop
```

### Deleting a Branch
```sh
# Delete a local branch
git branch -d <branch_name>

# Delete a remote branch
git push origin --delete <branch_name>
```

### Helpful Shortcuts
```sh
# Set the default branch to main
git branch -M main

# Show remote repositories
git remote -v

# Show the last commit
git show --stat HEAD
```

---
This guide covers the basics of Linux and Git for daily use. For more, check out:
- [Linux Documentation](https://linuxcommand.org/)
- [Git Documentation](https://git-scm.com/doc)
