## First-Time Push to a New GitHub Repo

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/USERNAME/REPO.git
git push -u origin main
```

## What Each Command Does

- `git init` - Starts git in your folder.
- `git add .` - Stages all files.
- `git commit -m "Initial commit"` - Creates the first commit.
- `git branch -M main` - Ensures the branch is named `main`.
- `git remote add origin ...` - Connects local repo to GitHub repo.
- `git push -u origin main` - Uploads code and sets upstream tracking.

## Useful Checks

```bash
git status
git remote -v
```