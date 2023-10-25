Git Commands:

git init = creates empty repository in the current directory

git add = add file to track file.. stages the added file
git add . = Add all files

git status = show if repository changes/ show changes

git commit = logs all changes in git - check in for changes

git commit -m = log change with comment

states of files:
modified = has changes since last commit,
staged = included in the next commit
commited = all changes have been commited

git log = show file history for current files

git clone = clone a repsoitory to a local directory

git push = origin(exp.main) load local repository or changes to remote repository

git pull = download content from remote repository

git:(main) code . = Open with VS

git remote add (origin) = upload your local repo back

git -v = see to where your local repo is conected

BRANCHES:
BRANCHES workflow:

//git checkout = go to other branch

name branch style example = my-new-branch

//git switch /branch_name = switch to another branch

git switch -c "new_branch_name" = creates a new branch and changes to this branch

git push -u origin "branch_name" = first push of the branch
after that first push you can use only = git push

create pull request = after push check the link for PR (remote:....)
go there to GH and create PR
GH ask can we merge?
When no conflict than merge PR

Pull Request is the combination of:
git fetch = getb branch
git merge =merge branches

After PR do again: = git pull origin main ...

other BRANCH Commands:

git switch main = go back to main

git branch show all branches in repository

git branch -a = list all branches local and remote

git branch -d = delete a branch
