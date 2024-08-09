# COMMON GIT COMMANDS

**git clone**
- Create a local copy of a remote repository
```sh
git clone <git-repository-url>
```
&nbsp;

**git status**

- Display the state of the working directory and the staging area.
```sh
git status
```
&nbsp;

**git add**

- Add file contents to the staging area for the next commit.

```sh
git add <file-name>
```

- Add all new and changed files to the staging area
```sh
git add -A
```
&nbsp;

**git commit**
- Record changes to the repository.
```sh
git commit -m '<type>(optional scope): <description>'
```
&nbsp;

**git push**
- Upload Local Repository to Remote Repository
```sh
git push <Remote
```
&nbsp;

**git pull**
- Fetch from and integrate with another repository or a local branch.
```sh
git pull <remote-name> <branch-name>
```
&nbsp;

**git branch**
- This command lists all the local branches in the current repository.
```sh
git branch
```
- This command lists all the remote branches in the current repository.
```sh
git branch -r
```
- This command creates a new branch.
```sh
git branch <branch name>
````
- This command deletes the feature branch.
```sh
git branch -d <branch name>  
```
&nbsp;

**git checkout**
- This command is used to switch from one branch to another.
```sh
git checkout <branch name>
```
- This command creates a new branch and also switches to it.
```sh
git checkout -b <branch name>
```
&nbsp;

**git merge**
- This command merges the specified branch’s history into the current branch.
```sh
git merge <branch name>
```
&nbsp;

**git reset**
- This command unstages the file, but it preserves the file contents.
```sh
git reset <file>
```
- This command undoes all the commits after the specified commit and preserves the changes locally.
```sh
git reset <commit>
```
- This command discards all history and goes back to the specified commit.
```sh
git reset -hard <commit>
```

