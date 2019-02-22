# Some GIT commands through gitbash
## https://www.dataschool.io/git-quick-reference-for-beginners/

````
Changing the working directory
````
$ cd ~/desktop

````
Cloning a repository
````
$ git clone https://github.com/chrismgentry/chemstats.git

````
Opening a local repository
````
$ cd chemstats

````
Listing the files in the repository
````
$ ls

````
Checking remotes (references to repositories that are not local
````
$ git remote -v

````
Creating a new file
````
$ touch new.md

````
Track modified and new files in a repository
````
git status

````
Stagging new and edited files for committing to the repository
By name adds individuals and . adds everything at once
````
git add .

````
Committing changes to the repository
Using -m "text" adds message to the commit
````
git commit

````
Checking local repository for the changes
````
git log

````
Pushing changes to GitHub
````
git push origin master
