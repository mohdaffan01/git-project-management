


# Git Branching and Stashing Guide

## 1. Creating Branches

### Create a New Branch
```bash
git branch feature/navbar
```
`feature/navbar` is the name of the new branch.

### Create and Switch to a New Branch
```bash
git switch -c feature/footer
```

### Check All Branches
```bash
git branch
```

### Switch to Another Branch
```bash
git switch feature/navbar
```

---

# 2. Merging a Branch into Main

### Step 1: Switch to the Main Branch
```bash
git switch main
```

### Step 2: Merge the Branch
```bash
git merge feature/navbar
```

---

# 3. Merge Conflicts

A **merge conflict** occurs when:

- Two branches modify the **same file**
- The modification happens on the **same line of code**

Git provides three options to resolve the conflict:

1. **Accept Current Change**  
   Keeps the changes from the **current branch (main)**.

2. **Accept Incoming Change**  
   Keeps the changes from the **branch being merged**.

3. **Accept Both Changes**  
   Keeps changes from **both branches**.

After resolving the conflict, you must **commit the changes again**.

---

# 4. Merging Techniques

Common Git merge strategies:

- Fast Forward Merge (FF Merge)
- Three-Way Merge
- Squash Merge
- Recursive Strategy Merge
- Rebase and Merge

---

# 5. Delete a Branch

```bash
git branch -d feature/navbar
```

---

# 6. Git Stashing

**Git stash** temporarily saves uncommitted changes so you can switch branches without committing them.

### Stash Changes
```bash
git stash
```

### Apply Stashed Changes
```bash
git stash apply
```

### Clear All Stashes
```bash
git stash clear
```