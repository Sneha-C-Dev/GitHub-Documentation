## Basic git commands

## 1. _Git add_
Moves changes from the working directory to the staging area. This gives you the opportunity to prepare a snapshot before committing it to the official history.
## 2. _Git branch_
This command is your general-purpose branch administration tool. It lets you create isolated development environments within a single repository.
## 3. _Git clean_
Removes untracked files from the working directory. This is the logical counterpart to git reset, which (typically) only operates on tracked files.
## 4. _Git clone_
Creates a copy of an existing Git repository. Cloning is the most common way for developers to obtain a working copy of a central repository.
## 5. _Git commit_
Takes the staged snapshot and commits it to the project history. Combined with git add, this defines the basic workflow for all Git users.
## 6. _git config_
A convenient way to set configuration options for your Git installation. You’ll typically only need to use this immediately after installing Git on a new development machine.
## 7. _git init_
Initializes a new Git repository. If you want to place a project under revision control, this is the first command you need to learn.
## 8. _git log_
Lets you explore the previous revisions of a project. It provides several formatting options for displaying committed snapshots.
## 9. _git merge_
A powerful way to integrate changes from divergent branches. After forking the project history with git branch, git merge lets you put it back together again.
## 10. _git pull_
Pulling is the automated version of git fetch. It downloads a branch from a remote repository, then immediately merges it into the current branch. This is the Git equivalent of svn update.
## 11. _git push_
Pushing is the opposite of fetching (with a few caveats). It lets you move a local branch to another repository, which serves as a convenient way to publish contributions. This is like svn commit, but it sends a series of commits instead of a single changeset
