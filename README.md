# Training_Assignment
1. `git init` - initialize local repository
1. `touch test.txt` - create a test.txt
1. Edited test.txt
1. `touch .gitignore` - empty gitignore(This can avoid unwanted files)
1. `git add .` (Staged of all files in master)
1. `git commit` (Commit in master)
1. `git remote add origin url` (Remote repository for pushing local files)
1. `git push --set-upstream origin master`(Create a remote master branch and push the local files)
1. `git checkout -b feature`(Created a new branch called feature and switched to it)
1. `git merge master`(Merge files from master to feature)
1. `git push --upstream origin feature`
1. Played with "`git rm rf --cached test.txt`" in between `git add .`
1. Created merge conflict by editing same line in test.txt from master and feature.
1. Added both changes from vs code.
1. Pushed master
1. Merged master to feature.
1. Pushed feature.
1. Created README.md in remote repository.
1. `git pull` to pull README.md
1. `git logs`(Check logs)
1. `git diff id1 id2`(Difference between two commits)
1. `git tag name` created a tag.
1. `mkdir code` Created a directory named code in feature
1. Added app.js in code folder
1. `git push` pushed it remote server
1. `git checkout master` Switched to master
1. `git pull` pulled updated README.md
1. `git merge feature` merged feature to master branch
1. `git push` pushed master branch
1. Edited README.md locally
1. `git status`
1. `git add .` Stage locally edited README.md
1. `git commit`
1. `git push`
