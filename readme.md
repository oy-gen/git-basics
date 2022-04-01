# Git Cheatsheet

## git repository

- `git init` = Initialize a new Git repository in current folder
- `git status` = Check information, changes and commit status

## commit

- `git add` = add changes for staging. Add . = everything ; Add foldername/filename 
- `git commit -m <commit message>` = perform commit with comment
- `git log` = 

## how to return to save points

- `git restore <file name>` = restore working tree files (rollback)
- `git restore --staged <file name>` = Unstage working tree files

## remote repository

- `git remote add origin <ssh link>` = Assign online repository to local folders via ssh link
- `git remote remove origin <ssh link>` = Remove assigned online repository (to re-connect with new one)
- `git remote -v` = 
- `git push -u origin <branch name>` - establish 
- `git push` - upload
- `git pull -u origin <branch name>` - establish
- `git pull` - download

## branching

- `git branch` - shows existing branches
- `git branch <branch name>` - create new branch
- `git switch` - switch from one brach to another

