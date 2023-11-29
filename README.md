# Git


## Initial Project

1. Start new project
```
git init
```

2. Add README.md file
```
git add README.md
```

3. First commit
```
git commit -m "first commit"
```

4. Rename branch to master
```
 git branch -M master
```

5. Create the remote repository
```
git remote add origin git@github.com:brjatoba92/Git-Commands-Use-For-Build-Projects.git
```

6. Send to GitHub
```
 git push -u origin master
```

## Main Commands

### Add files
1. All files 
```
git add . 
```

2. One file
```
git add file
```


### Add New Commit
```
git commit -m "one commit"
```


### Send to remote repository

1. One specify branch
```
git push origin branch_name
```

2. Branch master/main - not good practice
```
git push
```

### Download new update to master local branch
```
git pull
``` 