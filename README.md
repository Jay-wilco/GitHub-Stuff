README FOR GITHUB TASK

- created new repository for github.com
- created a new local repository for testing
- made commits in remote repository
- tried to pull in local:

hint: You have divergent branches and need to specify how to reconcile them.
hint: You can do so by running one of the following commands sometime before
hint: your next pull:
hint:
hint: git config pull.rebase false # merge

- merged repositories with "git config pull.rebase false"

received error: Your local changes to the following files would be overwritten by merge:
README.md
Please commit your changes or stash them before you merge.
Aborting
Merge with strategy ort failed.

- add . and commit changes in local and pulled again.
- > file updated with remote data

how to avoid this? NEVER MAKE COMMITS IN REMOTE! :)

changed branch to "test_branch" with git checkout -b test_branch

for practice, changed the branch to "main"
