


# How to Add a New Project to GitHub

This guide explains how to add a newly created project to GitHub.

## Steps

### Step 1: Open the root repository folder
Open the folder that is already connected to GitHub.

---

### Step 2: Add the project inside the root folder
Create or copy your project folder inside the root repository.

---

### Step 3: Make sure unnecessary files are ignored
Check that `.gitignore` exists and includes files like:
node_modules
dist
build
.env


---

### Step 4: Add files to Git
Run this command inside the root repository folder:
```
git add .
```

---

### Step 4: Add files to Git
Run this command inside the root repository folder:
```
git add .
```

### Step 5: Commit the project

Save the changes with a commit message:

```
git commit -m "Added new project"
```

Step 6: Push the project to GitHub

Upload the project to GitHub:

```
git push
```
