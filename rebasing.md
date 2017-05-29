###### A rebase takes the commits from another ancestor branch that occurred after you branched or last merged from that branch and applies them to your current branch. It does this by taking all of the current branch changes that do not exist on the ancestor branch and essentially removing them and setting them aside temporarily. It then takes the new changes from the ancestor branch and applies them onto your branch, then it reapplies your previous changes afterwards. This creates a straight line of commits that can then be fast forward merged easily. 

Task | Command(s)
--- | ---
Rebase the current branch from the master branch's HEAD | git rebase master
Abort a rebase attempt | git rebase --abort
Pull down origin branch changes and rebase onto current local branch | git pull --rebase
Do an interactive rebase for the last 5 commits on the current branch | git rebase -i HEAD~5