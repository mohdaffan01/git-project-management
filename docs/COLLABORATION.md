# Git Collaboration Workflow
 
## Main User Setup
1. Create project folder → push to GitHub
2. Go to **Settings → Collaborators** → add username
 
## Collaborator Setup
1. Accept email invite from GitHub
2. Clone the repo
3. Create a new branch *(important)*
4. Write code → commit → push branch:
```bash
git push -u origin <branch-name>
```
 
## Merger (Main User) — Fetch & Merge
```bash
git fetch                   # get collaborator's branch
git switch <branch-name>    # switch to their branch
git merge                   # merge into main
git push                    # push merged code to GitHub
```
 
> After push, notify the collaborator to sync:
```bash
git fetch
git pull origin main
```


