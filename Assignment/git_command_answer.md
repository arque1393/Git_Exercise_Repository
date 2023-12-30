# 7. Now, create one folder with the name Assignment. And add the following assignments to that folder. (4 points)


## 2. Answers the following git commands and add the file into the folder
- Provide commands for below operation

<hr>


### 1. Command to initialize git repository
```bash
git init
```

### 2. Command to clone remote repository
```bash
git clone <url_address_of_remote_git_repository>
```

### 3. Command to stage all changes
```bash
git add --all
```

### 4. Command to view state of working directory and staging area
```bash
git status
```

### 5. Command to create new branch
```bash
git branch <new_branch_name>
```

### 6. Command to change branch
```bash
git checkout <branch_name>
```

### 7. Command to clean staging area
```bash
git reset
```

### 8. Command to get commits and changes from remote branch (It should not merge changes in current branch).
```bash
git fetch <remote_branch_name>:<local_branch_name>
```
### 9. Command to get commits and changes from remote branch (It should merge changes in current branch).
```bash
git pull <remote_branch_name>
```

### 10. Command to cherry pick commit which SHA => 092018283103810930
```bash
git cherry-pick 092018283103810930
```

### 11. Command to push branch
```bash
git push origin <branch_name>
```

### 13. Command to delete remote branch
```bash
git push origin --delete <branch_name>
```

### 14. Command to do iterative rebase
```bash
git rebase -i HEAD~<number_of_commits>
```

