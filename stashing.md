Task | Command(s)
--- | ---
Stash all modified & 'tracked' changes | git stash
Stash all changes, including untracked files | git stash -u
Apply the newest stash | git stash apply
Delete the newest stash | git stash drop 
Apply & then delete the latest stash | git stash pop
Create a stash with a specific name | git stash save "my stash name"
Create a branch from the latest stash | git stash branch "new branch name"
Get a list of all stashes | git stash list
Apply a specific stash at index 1 | git stash apply stash@{1}