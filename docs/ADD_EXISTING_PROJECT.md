
---


# ---Add an Already Created Project---

```md
# How to Add an Existing Project to GitHub

Use this guide when the project is already created on your system.

## Steps
1. Copy the project folder into the root repository
2. Remove any existing `.git` folder inside the project
3. Make sure ignored files are excluded
4. Add and commit the project

## Commands
```bash
rm -rf project-name/.git
git add project-name
git commit -m "Added existing project"
git push
```

