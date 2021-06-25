# Class-67

git divides our work into 3 stages
1. working directory (where we are creating and making changes to our files)
we do (git add {filename})

2. staging area (where the files are ready to be commited)
we do (git commit -m "AnyMessage")

3. local git repository (after the files are commited, they become part of commit history in a local repository)
we do (git push)

4. there is a remote repository where we can push all our work

(git pull) is used to get the file from remote repository to local repository.
------------------------------------------

git init - initialize your repositry
git start - tracking changes in your file
git clone
git diff --staged (shown difference between the working directory and the previous commits)
git log - shows all your commits with commit ID 
git checkout {Commit ID} - commit id is the first 5 charecters of the commit ID
git branch - shows all the branches in your local repository
git checkout {branchname} - switch to a particular branch
git branch {branch name} - to create a new branch
git diff {branchA} {branchB} - to see the difference between the 2 branches
git remote add origin {the remote github link of the empty folder}
git push origin master - it will take the code to the remote github URL

BY default the branch is master.
-----------------------------------

git add {file name}
git commit -m "anymessage"
git remote add {remote repository name} {remote URL of the empty github link}
git push - push the current local repository to remote
git clone {URL}
git status
