# Git Commands
git --version                    → show Git version
git config --list                → show Git configuration
git status                       → show repository status
git init                         → initialize Git repository
git clone <url>                  → clone repository
git remote -v                    → show remote repositories
git add <file>                   → stage file
git add .                        → stage all changes
git restore <file>               → discard changes in file
git restore --staged <file>      → unstage file
git commit -m "message"          → create commit
git reset --soft HEAD~1          → undo your last commit while keeping your changes staged
git log                          → show commit history
git log --oneline                → compact commit history
git branch                       → list branches
git branch <name>                → create branch
git branch -d <name>             → delete branch
git switch <branch>              → switch branch
git switch -c <name>             → create and switch to branch
git merge <branch>               → merge branch into current branch
git pull                         → download and integrate remote changes
git push                         → upload local commits
git push -u origin <branch>      → push branch and set upstream
git diff                         → show unstaged changes
git diff --staged                → show staged changes
git rm <file>                    → remove file from Git
git mv <old> <new>               → move / rename tracked file
git stash                        → PENDING!                  

## Basic Git Workflow
git status
git add .
git commit -m "commit message"
git push

## Create a New Repository
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin <url>
git push -u origin main

## Clone an Existing Repository
git clone <url>
cd <repository>

## Branch Workflow
git switch -c feature/new-pipeline
git add .
git commit -m "Add new pipeline"
git push -u origin feature/new-pipeline

## Common Data Engineering Examples
git status
git pull
git switch -c feature/add-data-validation
git add src/
git commit -m "Add data validation"
git push -u origin feature/add-data-validation
