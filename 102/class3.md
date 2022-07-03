# Class 3

## What is VCS?

- VCS stands for version control system
- It allows you to save multiple version of something and keep track of all changes

## What is Git?

- Git is a VCS

## Git file states

- Files in Git have 3 main states: commited, modified, and staged
  - committed - file is stored in local database
  - modified - file has been changed but not stored in database
  - staged - file is ready to be put into database

## Logging in to Git in the terminal

- You can log into git using the following commands
  - `git config --global user.name "Jane Smith"`
  - `git config --global user.email "example@email.com"`

## Initializing git in a directory

1. cd to the directory you want to use git in
2. use the command `git init`
3. use the command `git add filename.extension` to add files to git
4. use acp to modify and push files to git

## ACP

- A: git add - adds files to be commited
- C: git commit - adds commits to repo
- P: git push - sends commits to vcs

## Cloning a project

- `git clone github/url/you.want` will clone a repository into the current directory

## Check status of current files

- `git status` will show all files with the state modified or staged.
