```bash

git config <parameter> <value>
Utility : To set details to the main configuration file.

git init
Utility : To initialise a git repository for a new or existing project.

git clone <repository url>
Utility : To copy a git repository from remote source, also sets the remote to original source so that you can pull again.

git branch
Utility : Lists out all the branches.

git checkout -b <branch name> (to create new branch from your current branch)
git checkout <branch name> (to change to an exisiting branch)
Utility : Switch to different branches

git stash
Utility : Save changes that you don’t want to commit immediately.

git stash pop
Utility : To apply saved changes that you have stashed before.

git add <path of file to be staged> or git add . (to stage all modified files)
Utility : adds changes to stage/index in your working directory.

git commit -m "<commit message>"
Utility : commits your changes and sets it to new commit object for your remote.

git reset --<mode> <revert to>
MODE:
  hard - resets changes to specific commit, will override all your local changes
  soft - stages changes to specific commit, doesn't override you local changes
REVERT TO:
  esither use COMMIT ID or HEAD~1(number of commit to move backwards)
Utility : You know when you commit changes that are not complete, this sets your index to the latest commit that you want to work on with.

git push -u <remote> <branch name> (to push to newly crated branch)
git push <remote> <branch name> (to push to exisitng branch)
git pull <remote> <branch name>
Utility : Push or Pull your changes to remote. If you have added and committed your changes and you want to push them. Or if your remote has updated and you want those latest changes.

```
