- clone git repo

```code
git clone <https://name-of-the-repository-link>
```
- git init and add remote 
```code
git init
git add .
git remote add <repo-link>
```
- show origin remote

```code
git remote show origin
```

- create branch and switch branch
```code
git branch <branchName>
git checkout <branchName>
git checkout -b <name-of-your-branch>
```

- delete branch
```code
git branch -d <branch-name>
```
- show the current git status and changes
```
git status
```

- To add changes to git
```code
git add <file> (only file)
git add . (for all changes in current directory)
```

- commit to git repo and push 
```code
git commit -m "commit message"
git push <remote> <branch-name>
```

- However, if the branch is newly created, then  also need to upload the branch with the following command:
```code
git push --set-upstream <remote> <name-of-your-branch>

(or)

git push -u origin <branch_name>
```

- Sometimes, need to revert your changes, use the command
```code
git log --oneline
git revert <commid-id>
```

- Fetching branch to local
```code
git fetch -p (remove delete branch and pull new branch)

(or)

git fetch origin <branch-name>
```

- Git pull for changes
```code
git pull origin <branch-name> 

(or) 

git pull
```

- remove unessary commit and update to one commit
```code
git reset --soft <commid-id>
git commit -m "commit name"
git push -f origin <branch-name>
```

