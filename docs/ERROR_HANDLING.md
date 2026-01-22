


# Common Git and GitHub Errors

## Folder shows arrow icon
Reason: The folder is a Git submodule  
Solution:
```
rm -rf project/.git
git rm --cached project
git add project



Accidentally pushed unwanted files

git rm -r --cached unwanted-folder

```

Authentication failed

Use GitHub Personal Access Token instead of password
