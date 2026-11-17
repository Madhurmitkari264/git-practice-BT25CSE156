Git Command                        Purpose

git --version                       Checks Git version.
git init                            Initializes a new Git repository.
git clone URL                       Downloads a repository from GitHub.
git status                          Shows the current status of files.
git add filename                    Adds a specific file to staging.
git add .                            Adds all changed files to staging.
git commit -m "message"             Saves changes with a commit message.
git push                            Uploads committed changes to GitHub.
git pull                            Downloads and merges remote changes.
git fetch                           Downloads remote changes without merging.
git branch                          Displays all local branches.
git branch name                     Creates a new branch.
git switch branchname               Switches to another branch.
git switch -c name                  Creates and switches to a new branch.
git checkout branchname             Switches to another branch.
git merge branchname                Combines another branch with current branch.
git branch -d name                  Deletes a branch.
git log                             Displays commit history.
git log --oneline                   Displays short commit history.
git diff                            Shows differences in files.
git restore filename                Discards unstaged changes in a file.
git reset filename                  Removes a file from staging.
git reset --hard                    Discards changes and resets to current commit.
git revert commit_id                Creates a new commit to undo an earlier commit.
git stash                           Temporarily saves unfinished changes.
git stash pop                       Restores and removes the latest stash.
git stash list                      Displays saved stashes.
git remote -v                       Shows connected remote repositories.
git remote add origin URL           Connects local repository to GitHub.
git remote remove origin            Removes a remote connection.
git tag                             Displays all tags.
git tag v1.0                        Creates a version tag.
git show                            Displays details of a commit.
git blame filename                  Shows who modified each line of a file.
git config --list                   Displays Git configuration.
git config --global user.name       Sets your Git username.
git config --global user.email      Sets your Git email.
git cherry-pick commit_id           Applies a specific commit to current branch.
git rebase branchname               Reapplies commits onto another branch.
git clean -fd                       Removes untracked files and directories.