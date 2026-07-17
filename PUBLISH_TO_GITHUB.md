# Publish to GitHub

## Recommended visibility

Create this repository as **private**.

## GitHub CLI

From the parent directory of this folder:

```bash
gh repo create hbycwyh2008/NOAI-IOAI-Preparation-Teacher-Keys --private --source ./NOAI-IOAI-Preparation-Teacher-Keys --remote origin --push
```

If the remote repository already exists:

```bash
cd NOAI-IOAI-Preparation-Teacher-Keys
git init
git add .
git commit -m "Initialize NOAI-IOAI-Preparation-Teacher-Keys"
git branch -M main
git remote add origin https://github.com/hbycwyh2008/NOAI-IOAI-Preparation-Teacher-Keys.git
git push -u origin main
```
