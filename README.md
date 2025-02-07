# My-Git-Commands


### Please tell me who you are.

 *  git config --global user.email "you@example.com"
 * git config --global user.name "Your Name"
 
### Getting & Creating Projects
| Command | Description |
| ------- | ----------- |
| `git init` | Initialize a local Git repository |
| `git clone ssh://git@github.com/[username]/[repository-name].git` | Create a local copy of a remote repository |

### Basic Snapshotting
| Command | Description |
| ------- | ----------- |
| `git status` | Check status |
| `git add [file-name.txt]` | Add a file to the staging area |
| `git add -A` | Add all new and changed files to the staging area |
| `git commit -m "[commit message]"` | Commit changes |
| `git rm -r [file-name.txt]` | Remove a file (or folder) |


### Branching & Merging
| Command | Description |
| ------- | ----------- |
| `git branch` | List branches (the asterisk denotes the current branch) |
| `git branch -a` | List all branches (local and remote) |
| `git branch [branch name]` | Create a new branch |
| `git branch -d [branch name]` | Delete a branch |
| `git push origin --delete [branch name]` | Delete a remote branch |
| `git checkout -b [branch name]` | Create a new branch and switch to it |
| `git checkout -b [branch name] origin/[branch name]` | Clone a remote branch and switch to it |
| `git branch -m [old branch name] [new branch name]` | Rename a local branch |
| `git checkout [branch name]` | Switch to a branch |
| `git checkout -` | Switch to the branch last checked out |
| `git checkout -- [file-name.txt]` | Discard changes to a file |
| `git merge [branch name]` | Merge a branch into the active branch |
| `git merge [source branch] [target branch]` | Merge a branch into a target branch |
| `git stash` | Stash changes in a dirty working directory |
| `git stash clear` | Remove all stashed entries |

### Sharing & Updating Projects
| Command | Description |
| ------- | ----------- |
| `git push origin [branch name]` | Push a branch to your remote repository |
| `git push -u origin [branch name]` | Push changes to remote repository (and remember the branch) |
| `git push` | Push changes to remote repository (remembered branch) |
| `git push origin --delete [branch name]` | Delete a remote branch |
| `git pull` | Update local repository to the newest commit |
| `git pull origin [branch name]` | Pull changes from remote repository |
| `git remote add origin ssh://git@github.com/[username]/[repository-name].git` | Add a remote repository |
| `git remote set-url origin ssh://git@github.com/[username]/[repository-name].git` | Set a repository's origin branch to SSH |

### Inspection & Comparison
| Command | Description |
| ------- | ----------- |
| `git log` | View changes |
| `git log --summary` | View changes (detailed) |
| `git log --oneline` | View changes (briefly) |
| `git diff [source branch] [target branch]` | Preview changes before merging |

### Extra
* git clone
* cd ruta
* git status
* git add .
* git status
* git commit --amend --no-edit --date="Jan 5 17:00:00 2020"
* git commit -m "FILE NAME" --date "Wed Jan 26 12:00 2025 +0000"
* git push -f origin master
* git config --global credential.helper wincred
* git config --global credential.helper cache
* Config file 
* git log origin/master or git log origin/main 

    [credential]
      helper = store

### Platforms

The following platforms can be used to host your repositories.

| Platform                           | Price |
| ---------------------------------- | ----- |
| [GitHub](https://github.com)       | Free  |
| [GitLab](https://gitlab.com)       | Free  |
| [Bitbucket](https://bitbucket.org) | Free  |

### Graphical User Interface (GUI)
Is the command-line interface not for you? Try one of the following clients.
| Clients                                      | Operational System |
| -------------------------------------------- | ------------------ |
| [Github](https://desktop.github.com)         | Mac and Windows    |
| [Source Tree](https://www.sourcetreeapp.com) | Mac and Windows    |
| [Tower](https://www.git-tower.com)           | MacOS and Windows  |

### History
| Key/Command                | Description                                                      |
| -------------------------- | ---------------------------------------------------------------- |
| `git log`                  | Lists version history for the current branch                     |
| `git log --author=[name]`  | Lists version history for the current branch from certain author |
| `git log --oneline`        | Lists compressed version history for the current branch          |
| `git show [commit]`        | Outputs metadata and content changes of the specified commit     |
| `git blame [file]`         | Shows who changed what and when in file                          |

### Gitignore
* You can list files/directories that you want to explicitely exclude from Git in a `.gitignore` file. This file should be placed at the root of your repository.
* It is noted that people usually exclude dependency caches, such as `node_modules`, system files, such as `.DS_Store`, among others.
* You can see the `.gitignore` file of [this repository](https://github.com/0nn0/git-basics-cheatsheet/blob/master/.gitignore) or [more examples](https://github.com/github/gitignore) provided by GitHub.

### Platforms
The following platforms can be used to host your repositories.
| Platform                           | Price |
| ---------------------------------- | ----- |
## #| [GitHub](https://github.com)       | Free  |remote: error: GH001: Large files detected.
| [GitLab](https://gitlab.com)       | Free  |
| [Bitbucket](https://bitbucket.org) | Free  |

### Git Markhow

https://guides.github.com/features/mastering-markdown/

### Git: Warnings

* **warning: LF will be replaced by CRLF** Solved: git config core.autocrlf true 

### Git remote: error: GH001: Large files detected.

git commit --amend -C HEAD

* git reset HEAD~1

* git reset HEAD~2

* git reset HEAD~3 

### fatal: the remote end hung up unexpectedly

 * git config http.postBuffer 524288000


