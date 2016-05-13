# git-cmds

Here the basic commands are listed with they operation 

Git Hub commands

1.git init

2.git status

#if any doc could present in current dir(in here octocat could present in here)

3.git add octocat.txt

2.again git status

#add changes in the docs 

4.git commit -m "Add cute octocat story"

# add same type files in same dir

5.git add '*.txt'

#comitting all changes

6.git commit -m 'Add all the octocat txt files'

#History

7.git log

#Remote Repositories

8.git remote add origin https://github.com/try-git/try_git.git

#Pulling Remotely

9.git pull origin master

#Differences

10.git diff HEAD

#Staged Differences

11.git add octofamily/octodog.txt

#Staged Differences (cont'd)

12.git diff --staged

#Resetting the Stage

13.git reset octofamily/octodog.txt

#Undo

14.git checkout -- octocat.txt

#Branching Out

15.git branch clean_up

#Switching Branches

16.git checkout clean_up

# Removing All The Things

17.git rm '*.txt'

#Commiting Branch Changes

18.git commit -m "Remove all the cats"

#Switching Back to master

19.git checkout master

#Preparing to Merge

20.git merge clean_up

# Keeping Things Clean
Congratulations! You just accomplished your first successful bugfix and merge. All that's left to do is clean up after yourself. Since you're done with the clean_up branch you don't need it anymore.

You can use git branch -d <branch name> to delete a branch. Go ahead and delete the clean_up branch now:

21.git branch -d clean_up

#The Final Push
Here we are, at the last step. I'm proud that you've made it this far, and it's been great learning Git with you. All that's left for you to do now is to push everything you've been working on to your remote repository, and you're done!

22.git push

