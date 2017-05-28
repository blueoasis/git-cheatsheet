Task | Command(s) 
--- | ---
Compare the state of the working directory to the staging area | git diff or (git difftool)
Compare the state of the working directory to the local repository (commited changes) | git diff HEAD or (git difftool HEAD)
Compare the state of the staging area to the local repository (commited changes) | git diff --staged or (git difftool --staged)
Compare a single file in the working directory against the staging area | git diff {path to file}
Compare a single file in the working directory against the local repo | git diff HEAD {path to file} or git difftool HEAD {path to file}
Compare a single file in the staging against the local repo | git diff --staged {path to file} or git difftool --staged {path to file}
Compare the latest commit to the one before it | git diff HEAD HEAD~1 or (git diff HEAD..HEAD~1) or (git diff HEAD HEAD^) or (git diff HEAD..HEAD^) (on zsh, you will need to add setopt NO_NOMATCH in your .zshrc file to be able to use the HEAD^ syntax, otherwise, use HEAD~1)
Compare the local master branch to the remote origin branch | git diff master origin/master
