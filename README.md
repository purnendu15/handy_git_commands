# handy_git_commands

# Branch Deletion
git branch -d branch_name

git branch -D branch_name

The 2nd command is forcefully doing it 

# Deleting the last commit locally and then remotely
Assumption: remote and locally pulled branch have the same head

git reset HEAD^ --hard

git push origin -f

