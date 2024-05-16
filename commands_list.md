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

- Go from local to remote
`git remote add origin <ssh-adress>` : This will create the link between local and remote repositories.

`git push` : will send all the commits to the remote repository.

On the first time you try to push, you might get an error"

```
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master
```