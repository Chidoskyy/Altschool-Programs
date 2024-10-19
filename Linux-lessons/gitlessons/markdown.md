# Git Lessons

The command `git config -l` (or `git config --list`) is used to list all the Git configuration settings for the current repository and user.  
It shows a list of key-value pairs that represent the configuration options, including:

---

## Git Config List Output

This is the outcome of typing the command `git config -l` on my system:

```bash
$ git config -l
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager-core
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.name=Chidiebere Uduh
user.email=udugreg@gmail.com
core.autocrlf=false
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true
remote.origin.url=https://github.com/Chidoskyy/Altschool-Programs
remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*
branch.main.remote=origin
branch.main.merge=refs/heads/main
branch.gitassighment.vscode-merge-base=origin/main


## Git Remote Command

The command `git remote -v` is used to display the URLs that Git has associated with remote repositories. The `-v` stands for "verbose," which means it will show the full URL of the remote repository along with its name and the type of access (fetch or push).

This is the outcome of typing the command `git remote -v`:

```bash
$ git remote -v
origin  https://github.com/Chidoskyy/Altschool-Programs (fetch)
origin  https://github.com/Chidoskyy/Altschool-Programs (push)



##

The `git log` command is used to display the commit history for the current Git repository. When you run this command, it provides a list of commits, showing important information about each commit, such as:

```bash
- **Commit hash**: A unique identifier for each commit (a long string of letters and numbers).
- **Author**: The name of the person who made the commit.
- **Date**: The date and time when the commit was made.
- **Commit message**: A brief description of the changes made in that commit.

Here is the outcome of running `git log` on my command line:

```bash
$ git log commit 989b4682ba542446e014188ff9baeff0b7eabba8 
(HEAD -> gitassighment, origin/master, origin/main, main) Author: 
Chidiebere Uduh udugreg@gmail.com Date: Sat Aug 24 21:45:38 2024 +0100
