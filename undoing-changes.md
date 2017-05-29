Task | Command(s)
--- | ---
Revert tracked, modified file to staged version | git checkout -- fileName
Revert staged file to committed version | git reset HEAD fileName
Change the last commit message | git commit --amend
Get the reflog of all changes | git reflog
Change the head pointer to another commit | git reset someCommitHash or git reset HEAD@{some ref index from git reflog}
Reset the HEAD to 5 revisions ago | git reset HEAD~5