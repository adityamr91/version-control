# GIT FREQUENTLY USED COMMANDS

git clone <repo>
Clone repo located at onto local machine. Original repo can be located on the local filesystem or on a remote machine via HTTP or SSH.

git branch 
List all of the branches in your repo. Add a <branch> argument to create a new branch with the name <branch>.

git checkout -b <branch>
Create and check out a new branch named <branch>. Drop the -b flag to checkout an existing branch.

git merge <branch> 
Merge <branch> into the current branch.

git fetch <remote> <branch>
Fetches a specific <branch>, from the repo. Leave off <branch> to fetch all remote refs.

git pull <remote>
Fetch the specified remote’s copy of current branch and immediately merge it into the local copy.

git push <remote> <branch>
Push the branch to <remote>, along with necessary commits and objects. Creates named branch in the remote repo if it doesn’t exist.

git commit
Replace the last commit with the staged changes and last commit combined. Use with nothing staged to edit the last commits message.

git commit -m "<message>"
Commit the staged snapshot, but instead of launching a text editor, use <message> as the commit message.

git status 
List which files are staged, unstaged, and untracked.

git diff
Show unstaged changes between your index and working directory
