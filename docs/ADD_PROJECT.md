


# How to Add a New Project to GitHub

This guide explains how to add a newly created project to GitHub.

## Steps

### Step 1: Open the root repository folder
Open the folder that is already connected to GitHub.
### Step 2: Add the project inside the root folder if any root folder
Create or copy your project folder inside the root repository.
### Step 3: Make sure unnecessary files are ignored
Check that `.gitignore` exists and includes files like:
```
node_modules
dist
build
.env
```
### Step 4: Add files to Git
### Step 5: Commit the project
### Step 6: Push the project to GitHub




### Commands for 1st time to add on github
```
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin REPO_URL
git push -u origin main

```
### after that

```
cd your-project-folder
git add .
git commit -m "message"
git push

```
