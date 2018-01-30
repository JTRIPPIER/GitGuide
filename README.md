# Git Reference
A quick reference to some commonly used git commands.

#### Set up a new repo using existing code base
``` 
  # create a repo
  git init
  
  # add a git ignore file
  
  # commit changes
  git add .
  git commit -m "initial commit"
  
  # set up the remote
  # Use '/' not '\' when defining a location on a server
  git remote add origin <location_of_remote>
  
  #Go to the location of the remote and create a bare repo
  git init --bare
  
  #push changes
  git push --set-upstream origin master
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

#### Move local commit to another branch(from master)
```
  git rebase origin/master          -- to ensure you have the latest changes
  git branch new_branch             -- create a new branch with the commits that are being kept
  git reset --hard origin/master    -- remove changes from master branch
```

#### DESC
```
  CODE
```
