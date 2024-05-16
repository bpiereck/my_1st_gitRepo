# Commands list

`git init` : initiliazes the local repository

`git status` : Check in what conceptual area your file is
Uncommited: is in the staging area
Unstaged: Git has an old version, but there are new changes 
Untracked: Completely new file, never seen it before

- basic routine

`git add <file_name>` : area to organize your 'library' structure, commits unit.

`git commit -m "meaninful msg"` : that will create a point (version) in my timeline

- Time traveling

`git log` : Check the history and access the unique ID's and authors
`git diff <id> <id>` : Check differences in two commits (start with oldest commit)
`git show <id>` / `git show <id> <id>` : show the changes that were made in a chosen commit
