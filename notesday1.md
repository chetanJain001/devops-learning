git init : used to initialize a new Git repository

git clone : used to clone (copy) a remote repository to the local machine

git status : used to display the state of the working directory and staging area

git branch : used to list all local branches available in the repository

git branch -a : used to list both local and remote branches

git branch -d <branch-name> : used to delete a local branch (only if it has been merged)

git branch -D <branch-name> : used to force delete a local branch

git checkout <branch-name> : used to switch to an existing branch

git checkout -b <branch-name> : used to create a new branch and switch to it

git add <file-name> : used to stage a specific file

git add . : used to stage all new and modified files

git commit -m "message" : used to commit the staged changes with a commit message

git log : used to display the commit history of the repository

git diff : used to display the differences between working directory, staging area, and commits

git fetch : used to download the latest changes from the remote repository without merging them into the local branch

git pull : used to fetch and merge the latest changes from the remote repository into the current branch

git push : used to push committed changes from the local repository to the remote repository

git merge <branch-name> : used to merge another branch into the current branch

git rebase <branch-name> : used to reapply commits on top of another branch to maintain a linear commit history

git stash : used to temporarily save uncommitted changes without committing them

git stash pop : used to restore the most recently stashed changes and remove them from the stash list

git remote -v : used to display the configured remote repositories along with their URLs

git reset --soft HEAD~1 : used to undo the last commit while keeping the changes staged

git reset --hard HEAD~1 : used to undo the last commit and permanently discard all changes

git restore <file-name> : used to discard local changes made to a file

git restore --staged <file-name> : used to unstage a staged file without losing its changes

git rm <file-name> : used to remove a file from both the working directory and the Git repository

git tag : used to list all tags in the repository

git tag <tag-name> : used to create a new tag for the current commit


