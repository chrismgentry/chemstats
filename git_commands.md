#Some GIT commands through gitbash

'''
Changing the working directory
'''
gentryc@404286DLE MINGW64 ~
$ cd ~/desktop

'''
Cloning a repository
'''
gentryc@404286DLE MINGW64 ~/desktop
$ git clone https://github.com/chrismgentry/chemstats.git
Cloning into 'chemstats'...
remote: Enumerating objects: 12, done.
remote: Total 12 (delta 0), reused 0 (delta 0), pack-reused 12
Unpacking objects: 100% (12/12), done.

'''
Opening a local repository
'''
gentryc@404286DLE MINGW64 ~/desktop
$ cd chemstats

'''
Listing the files in the repository
'''
gentryc@404286DLE MINGW64 ~/desktop/chemstats (master)
$ ls
CHEM4150_Script.txt  ChemData.xlsx  README.md

'''
Checking remotes (references to repositories that are not local
'''
gentryc@404286DLE MINGW64 ~/desktop/chemstats (master)
$ git remote -v
origin  https://github.com/chrismgentry/chemstats.git (fetch)
origin  https://github.com/chrismgentry/chemstats.git (push)

'''
Creating a new file
'''
gentryc@404286DLE MINGW64 ~/desktop/chemstats (master)
$ touch new.md

'''
Track modified and new files in a repository
'''
git status

'''
Stagging new and edited files for committing to the repository
By name adds individuals and . adds everything at once
'''
git add .

'''
Committing changes to the repository
Using -m "text" adds message to the commit
'''
git commit