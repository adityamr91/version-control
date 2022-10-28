# GIT FREQUENTLY USED COMMANDS

<b>git clone \<repo\></b><br />
Clone repo located at onto local machine. Original repo can be located on the local filesystem or on a remote machine via HTTP or SSH.

<b>git branch</b> <br />
List all of the branches in your repo. Add a \<branch\> argument to create a new branch with the name \<branch\>.

<b>git checkout -b \<branch\></b><br />
Create and check out a new branch named \<branch\>. Drop the -b flag to checkout an existing branch.

<b>git merge \<branch\> </b><br />
Merge \<branch\> into the current branch.

<b>git fetch \<remote\> \<branch\></b><br />
Fetches a specific \<branch\>, from the repo. Leave off \<branch\> to fetch all remote refs.

<b>git pull \<remote\></b><br />
Fetch the specified remote’s copy of current branch and immediately merge it into the local copy.

<b>git push \<remote\> \<branch\></b><br />
Push the branch to \<remote\>, along with necessary commits and objects. Creates named branch in the remote repo if it doesn’t exist.

  <b>git commit</b><br />
Replace the last commit with the staged changes and last commit combined. Use with nothing staged to edit the last commits message.

  <b>git commit -m "\<message\>" </b><br />
Commit the staged snapshot, but instead of launching a text editor, use \<message\> as the commit message.

<b>git status</b> <br />
List which files are staged, unstaged, and untracked.

<b>git diff</b><br />
Show unstaged changes between your index and working directory
