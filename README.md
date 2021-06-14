# Training_Assignment
1.git init - initialize local repository
2.touch test.txt
3.Edited test.txt
4.touch .gitignore - empty gitignore(This can avoid unwanted files)
5.git add . (Staged of all files in master)
6.git commit (Commit in master)
7.git remote add origin url (Remote repository for pushing local files)
8.git push --set-upstream origin master(Create a remote master branch and push the local files)
9.git checkout -b feature(Created a new branch called feature and switched to it)
10.git merge master(Merge files from master to feature)
11.git push --upstream origin feature
12.Played with "git rm rf --cached test.txt" in between git add .
13.Created merge conflict by editing same line in test.txt from master and feature.
14.Added both changes from vs code.
15.Pushed master
16.Merged master to feature.
17.Pushed feature.
18.Created README.md in remote repo.
19.git pull to pull README.md
20.git logs(Check logs)
21.git diff id1 id2(Difference between two commits)
22.created a tag.
