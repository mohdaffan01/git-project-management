

## Cheat Sheet

| Task | Command |
|------|---------|
| Set name (first time) | `git config --global user.name "Your Name"` |
| Set email (first time) | `git config --global user.email "email@example.com"` |
| Change name (normal) | `git config --global user.name "New Name"` |
| Change email (normal) | `git config --global user.email "new@email.com"` |
| Fix multiple values (name) | `git config --global --replace-all user.name "affan"` |
| Fix multiple values (email) | `git config --global --replace-all user.email "email@example.com"` |
| Set name for one repo only | `git config user.name "Name"` (no --global) |
| Set email for one repo only | `git config user.email "email@example.com"` (no --global) |
| Check name | `git config user.name` |
| Check email | `git config user.email` |
| Check all global settings | `git config --global --list` |

---