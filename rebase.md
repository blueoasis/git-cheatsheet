Task | Command(s)
--- | ---
Do an interactive rebase for the last 5 commits on the current branch | git rebase -i HEAD~5
Rebase the current branch from the master branch's HEAD | git rebase master
Abort a rebase attempt | git rebase --abort
Pull down origin branch changes and rebase onto current local branch | git pull --rebase