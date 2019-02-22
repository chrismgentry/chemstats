#Some GIT commands through gitbash

````
Changing the working directory
````
$ cd ~/desktop

````
Cloning a repository
````
$ git clone https://github.com/chrismgentry/chemstats.git
Cloning into 'chemstats'...
remote: Enumerating objects: 12, done.
remote: Total 12 (delta 0), reused 0 (delta 0), pack-reused 12
Unpacking objects: 100% (12/12), done.

````
Opening a local repository
````
$ cd chemstats

````
Listing the files in the repository
````
$ ls
CHEM4150_Script.txt  ChemData.xlsx  README.md

````
Checking remotes (references to repositories that are not local
````
$ git remote -v
origin  https://github.com/chrismgentry/chemstats.git (fetch)
origin  https://github.com/chrismgentry/chemstats.git (push)

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