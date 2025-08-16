# Common-Commands
Common Commands for Reference,


# Git Commands Reference (with Descriptions)

## 1. Initialize a new Git repository
*Use this when starting a new project directory with Git tracking.*
```sh
git init
```

## 2. Add a specific file to the staging area
*Use this to stage only main.py (or any specific file) for your next commit.*
```sh
git add main.py
```

## 3. Commit staged changes with a message
*Use this to save your staged changes to local history with a message describing what was changed.*
```sh
git commit -m "Your commit message"
```

## 4. Add a remote GitHub repository
*Use this to connect your local repository to a GitHub repo. Replace YOUR-USERNAME and YOUR-REPO.*
```sh
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
```

## 5. Rename your branch to main (optional, do once)
*Use this if your branch is not already named main. Only needed once per repo.*
```sh
git branch -M main
```

## 6. Push your code to GitHub (first time for a branch)
*Use this to upload your commits to GitHub. Do this the first time you push a new branch.*
```sh
git push -u origin main
```
*If pushing a different branch (like version1), replace main with your branch name:*
```sh
git push -u origin version1
```

## 7. Create and switch to a new branch
*Use this to make a separate version of your code without changing the original branch.*
```sh
git checkout -b version2
```

## 8. Switch between branches
*Use this to move back and forth between code versions (branches).*
```sh
git checkout main      # Switch to main branch
git checkout version2  # Switch to version2 branch
```

## 9. Stage and commit changes on your current branch
*Use these after you make changes to files you want to keep on this branch only.*
```sh
git add main.py
git commit -m "Describe your changes"
```

## 10. Push changes on the current branch to GitHub
*Use this to update your branch on GitHub after committing.*
```sh
git push
```
*If it’s the first push for this branch, use:*
```sh
git push -u origin version2
```

---

**Summary**:  
- `git init` – Start tracking a project with Git  
- `git add main.py` – Stage a specific file  
- `git commit -m "msg"` – Save changes with a message  
- `git remote add origin ...` – Connect to GitHub  
- `git branch -M main` – Rename branch to main (optional)  
- `git push -u origin <branch>` – Push branch to GitHub  
- `git checkout -b <branch>` – Create/switch to new branch  
- `git checkout <branch>` – Switch branches  
- `git push` – Update remote branch after commit  
