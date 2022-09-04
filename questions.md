##### 1. How to list all the branches?
A: To list all the branches, we use command called $git branch

##### 2. How to check all the possible commands of Git?
A: To check all the possible commands of Git, we use command called $git help --all

##### 3. How to check all the options of a command?
A: To check all the options of a command, we use command called $git command -help

##### 4. How to check the commit history?
A: To check the commit history, we use the command called $git log

##### 5. How to commit the changes?
A: To commit the changes,we use the command called $git commit -m <commit message>
  
##### 6. How to discard changes of a specific file (test.html) in the working directory?
A: To discard changes of a specific file (test.html) in the working directory, we use the command called $git restore <filename>
  
##### 7. How to stage the changes of a specific file (test.html)?
A: To stage the changes of a specific file, we use the command called,
  1.for staging the file, we use $git add <filename>
  2.for staging all files, we use $git add. (or) $git add -A (or) $git add --all
  
##### 8. What are the different ways to stage all the changes?
A: The different ways to stage all the changes are
   $git add. (or) $git add -A (or) $git add --all

##### 9. How to check the status?
A: To check the statuss, we use the command called $git status 
##### 10. How check status in short format?

##### 11. How to initialize the git?
A: To initialize the git, we use the command called $git init
  
##### 12. How to list all the configurations?
A: To list all the configurations, we use the command called $git config -l
  
##### 13. How to configure email for a specific repo?
A: To configure email for specific repo, we use the command called $git config user.email <email>
  
##### 14. How to configure email at global?
A: To configure email at global, we use the command called $git config --global user.email <email>
  
##### 15. How to configure user name at global?
A: To configure username at global, we use the command called $git config --global user.name <name>
  
##### 16. How to configure user name for a specific repo?
A: To configure name for specific repo, we use the command called $git config user.name <name>
  
##### 17. Explain how you will generate the SSH key?
A: to generate a SSH key, first run the ssh-keygen command,after that the algorithm is selected by using the -t option and the key size by using -b option.after that the tool prompts for the file in which to store the key,we use command ssh-keygen -f <filename> option.
  to us epublic authentication, the public key must be copied to the srver and installed in an authorized key file.
  this can be done by using ssh-copy-id tool. after that add key to ssh agent. 
##### 18. How to create a branch (my-first-branch)?
A: To create a branch , we use the command called $git branch <branch name>
  
##### 19. How to checkout to a branch (my-first-branch)?
A: To checkout to a branch , we use the command called $git checkout <branch name>
  
##### 20. How to create a branch & checkout to that branch (my-second-branch)?
A: To create a branch & checkout to that branch, we use the command called $git checkout -b <branch name>
  
##### 21. How to delete a branch (my-third-branch)?
A: To delete a branch, we use the command called $git branch -D <branch name>
  
##### 22. How to merge the branch (my-fourth-branch)?
A: To merge the branch, we use the command called $git merge <branch name>
  
##### 23. How to pull the changes from 'main' branch?
A: To pull the changes from 'main' branch, we use the command called $git pull origin master
  
##### 24. How to clone a repo using https url?
A: To clone a repo using https url, we use the command called $git clone <http url>
  
##### 25. How to clone a repo using ssh url?
A: To clone a repo using ssh url, we use the command called $git clone <ssh url >
  
##### 26. How to clone a repo from a specific branch?
A: To clone a repo from a specific branch, we use the command called $git clone -b <branch name> <http url (or) ssh url >
  
##### 27. How to roll back to a specific commit?
A: To rollback to a specific commit, we use the command called $git reset <commit id> (or) $git revert <commit id>
  
##### 28. How to change the commit message of the last commit?
A: To change the commit message of the last commit, we use the command called $git commit --amend -m <commit message>
  
##### 29. How to list all the stashes?
A: To list all the stashes, we use the command called $git stash list
  
##### 30. How to stash the changes?
A: To stash the changes, we use the command called, $git stash
  
##### 31. How to apply the topmost stash and leave it in the stash list?
A: To apply the topmost stash and leave it in the stash list, we use the command called $git stash apply
##### 32. How to apply the topmost stash and remove it from the stash list?
A: To apply the topmost stash and remove it from the stash list, we use the command called $git stash pop
##### 33. How to apply a specific stash based on the stash number?
A: To apply a specific stash based on the stash number, we use the command called $git stash apply stash@[number]
##### 34. How to drop a specific stash based on the stash number?
A: To drop a specific stash based on the stash number, we use the command called $git stash drop stash@[number]
  
##### 35. How to clear the complete stash list?
A: To clear the complete stash list, we use the command called, $git stash clear 
  
##### 36. Why we use .gitignore file?
A: We use this .gitignore file in the case of where the folders and files that are not required to be committed like log files , when we perform any action, in the log files, that action will get logged into this log file and that information is only confined to the local environment.so in such case there is no need of anything to push this log files in to git repo. So for that case in the .gitignore file, we mention or specify  the files or folders that shouldn't to be tracked, this is the reason why we use .gitignore file.
