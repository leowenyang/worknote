git note
==============================
repo manage
-------------------------
repo operator is belw

    git init    => create new repo
    git clone   => clone a remote repo
    git add     => add file into Stage
    git commit  => add stage file into repo

code merge
-------------------------
code merge is realize by branch

    git branch {branch name} tag   => create a branch with tag(start point)
    git rebase {branch name}       => merge all the lates modify 
    git merge  {branch name}       => merge branch to current branch

code rollback
-------------------------

    git reset HEAD          => restore file from Stage
    git reset HEAD^ --soft  => cancel last commit, but save workspace modify 
    git reset HEAD^ --hard  => cancel last commit, no save workspace modify
