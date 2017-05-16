# Git Reference
A quick reference to some commonly used git commands.

#### Set up a new repo using existing code base
``` 
  git init
  git add .
  git commit
```

#### Remove all changes
``` 
  git init
  git add .
  git commit
```

#### Set up a new branch
``` 
  git checkout -b <Branch-name>
```

#### Pulling
```
  git pull
```


#### Pushing
```
  git push
  git push -f (Force)
  git push -u origin HEAD (set upstream branch)
```

#### Rebasing
```
  git rebase 
```

#### Merging
```
  git merge 
```

#### Tidy up 
Force clean remove untracked files and directories
```
  git clean -df
```

#### Others 
Search the logs
```
  git log -S <search-string>
```

#### Remove all local changes and get the latest
```
  git ???
```

#### Undoing a change
```
  git checkout -- [filename.txt]
```
#### Rename a branch
```
  git branch -m old_branch new_branch
  git push origin :old_branch  
  git push --set-upstream origin new_branch
```

#### DESC
```
  CODE
```
