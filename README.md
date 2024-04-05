# git-commands
GitHub commands that are almost enough on a day-to-day basis for a Software Engineer
## At the start of your development, you need to use the below commands.
### 1. Initialize a local Git repository
```
git init
```

### 2. Create a local copy of a remote repository
```
git clone [URL]
```
You can get the above URL from “code” in your repository. Click on the icon next to the URL to copy.

### 3. List branches
```
git branch
```

### 4. List all branches
```
git branch -a
```

### 5. Switch to a branch
```
git checkout [branch name]
```

### 6. Create a new branch and switch to it
```
git checkout -b [branch name]
```
If you want to pull the latest changes from any branch, you can use the below command.

### 7. Pull changes from remote repository. This command is very important to avoid your changes overwriting your team member changes.
```
git pull origin [branch name]
```

## Once your development work is over and files are saved, you can use the below commands.
### 8. Check status
```
git status
```

### 9. Add all new and changed files to the staging area
```
git add -A
```

### 10. Commit changes
```
git commit -m "[commit message]"
```

### 11. Push changes to remote repository
```
git push
```

### 12. Push changes to a particular upstream
```
git push --set-upstream origin [branch name]
```

You’re all set.
