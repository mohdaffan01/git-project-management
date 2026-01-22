


---


# ---Managing Multiple Projects in One Repository---


# Root Repository Structure

A single repository can contain multiple projects.

## Recommended Structure


root-repo/
├── project-one/
├── project-two/
├── project-three/
├── docs/
└── .gitignore


## .gitignore (Example)
**/node_modules
**/dist
**/build
.env
*.log



## Common Mistakes
- Initializing Git inside sub-projects
- Pushing dependency folders
- Using unclear project names
