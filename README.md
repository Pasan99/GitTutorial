# Git Commands

##### Initialize a git repository

> git inti

##### Add files to the staging area

Add all the files to staging area

> git add .
> Or you can add specific files
> git add index.html

##### See all the files in the staging directory

> git status

##### Commit files which are in the staging area

> git commit -m 'Initial Commit'
> -m stands for message. As a best practice for every commit we should provide a meaningful message. So that, we know what changes we made.

##### Create new branch

> git branch Pasan
> This will create a new branch named 'Pasan'

##### Move to the newly created branch

> git checkout Pasan

##### Merge new changes from new branch to the master

First you need to move back to the master

> git checkout master
> Then you can merge the changes
> git merge Pasan

##### Adding remote repository

> git remote add origin https://github.com/Pasan99/GitTutorial.git

##### Push changes to the remote branch

> git push -u origin master
