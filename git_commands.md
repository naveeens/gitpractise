- git config *to add user name and email of the owner of repo*
	- git config --get <key> *get the value of the key*
	- git config --list *to list all settings*
	- git config --global alias.<name> command *to create aliases*
- git init [dirname] *to initialize a git repository*
- git clone [-branch <branch_name>] <remote_repo_url>


- git status *to list status of current files in the repo. i.e, staged, unstaged, and untracked files*
- git add *to add the unstaged changes for the next commit*
- git rm *removes file from staging and working tree*
- git add -am "commit message"
- git stash [-u, --all] *save staged and unstaged changes to stash for later use*
- git stash pop, apply and drop
- git commit *to save a snapshot of all the staged changes*
- git commit --amend -m "new commit message"
- git log *shows a log of commits*
- git diff *difference between two commits, branches, files, current and recent commit*

- git branch [--list, -a]
- git branch <new_branch_name>
- git checkout <branch__name> *switch into an existing branch. use -b to create and checkout*
- git branch -d <branch_name> *safe delete local branch -D for force delete*
- git branch -m <new_name>
### merging a branch into the main branch
	- git checkout main
	- git merge <branch name>
- git push remote_repo branch


- git fetch remote [branch]
- git merge remote branch
- git pull remote


- git remote *list all remote repos*
- git remote add <name> <url_to_remote>
- git remote rm <name>
- git remote rename <old> <new>


- git reset *resets working, staging and commits trees depending on the args*
- git restore *unstage or even restore working tree to last commit*
- git revert *inverses changes and adds it as new commit*
- git checkout head~3
- git checkout <commit_id>
- 
