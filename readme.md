# Git Cheatsheet

## git repository

- `git init` = Initialize a new Git repository in current folder
- `git status` = Check information, changes and commit status

## commit

- `git add` = add changes for staging. Add . = everything ; Add foldername/filename 
- `git commit -m <commit message>` = perform commit with comment
- `git commit <filename> --amend --no-edit` = add file to current commit without editing "message"
- `git log` = check commits
- `git log -p` = shows more meta info about changes

## how to return to save points

- `git restore <file name>` = restore working tree files (rollback)
- `git restore --staged <file name>` = Unstage working tree files

## remote repository

- `git fetch -a`- check meta info remotely (a=all)
- `git remote add origin <ssh link>` = Assign online repository to local folders via ssh link
- `git remote remove origin <ssh link>` = Remove assigned online repository (to re-connect with new one)
- `git remote -v` = 
- `git push -u origin <branch name>` - push to new remote branch 
- `git push` - upload
- `git pull -u origin <branch name>` - Downloads branch
- `git merge origin <branch name>` - Downloads(pulls) branch and merges with branch locally
- `git pull` - download

- `git clone <SSH link>` - clone remote repository to local, according folders are created

## branching

- `git branch -d <branch-name>` - delete branch
- `git branch` - shows existing branches
- `git branch -a` - shows existing branches, also remote ones (a=all)
- `git branch <branch name>` - create new branch
- `git switch <branchname>` - switch from one brach to another
- `git checkout -b <branch name>` - check out if brach exists, if not create it
- `git switch -c <branchname>` - switches branch by creating a new one
- `git checkout -- <file-name>` discard changes
- `git merge main' - Von einem aktiven branch aus, den Up-to-date status des main branches mit dem aktuellen branch mergen.
