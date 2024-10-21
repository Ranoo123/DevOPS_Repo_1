# Commands for GIT and Linux Operations

## 1. Basic Linux Commands
- `ls` – List directory contents
- `pwd` – Print current working directory
- `ll` – List directory contents in long format
- `mkdir GIT_For_DevOPS` – Create a directory named "GIT_For_DevOPS"
- `cd GIT_For_DevOPS/` – Change directory to "GIT_For_DevOPS"
- `rm -rf *` – Remove all files and directories forcefully
- `touch file_name` – Create a new empty file
- `vi file_name` – Edit or create a file using the `vi` text editor
- `cat file_name` – Display the contents of a file
- `clear` – Clear the terminal screen
- `rm file_name` – Remove a file

## 2. Git Initialization and Repository Setup
- `git init` – Initialize an empty Git repository
- `git status` – Show the working directory and staging area status
- `git log` – Display the commit history
- `git log --oneline` – Show a concise commit history in one line per commit
- `git add file_name` – Stage a file for committing
- `git rm --cached file_name` – Unstage a file without deleting it

## 3. Git Commit Operations
- `git commit -m "commit message"` – Commit the staged changes with a message
- `git restore file_name` – Restore a deleted file to its previous state

## 4. Branch Management in Git
- `git branch` – List all branches in the repository
- `git checkout branch_name` – Switch to a specific branch
- `git checkout -b branch_name` – Create a new branch and switch to it
- `git branch -b Test` – Create a new branch named "Test"

## 5. File Operations with Git
- `touch file1.txt file2.txt` – Create multiple files
- `git add file1.txt file2.txt` – Stage multiple files for committing
- `git commit -m "adding file1.txt and file2.txt"` – Commit staged files with a message

## 6. Merge and Checkout Operations
- `git checkout master` – Switch to the master branch
- `git checkout dev` – Switch to the dev branch

## 7. File Listing and Permissions
- `ls -l` – List files in long format with file permissions
- `ls -a` – List all files, including hidden files

## 8. Miscellaneous Operations
- `history` – Show command history
- `cls` – Clear the terminal
