# Play---Githug
This repo is used to write down the answers for questions in small program game 'Githug' and some notes

## Before Start, how to play?
```
Download Ruby, install githug, use 4 game commands: (githug play(check if answer if right) githug hint (get hint for current level) githug reset (reset current level or a given level) githug levels (list all levels))
```
## Level 1 - init
### Difficulty: *
#### Question: A new directory, `git_hug`, has been created; initialize an empty repository in it.
### Answer: 
```
git init
```

## Level 2 - config
### Difficulty: *
#### Question: Set up your git name and email, this is important so that your commits can be identified.
### Answer: 
```
git config user.name 'Yang'
git config user.email 'daiyang71@gmail.com'
```

## Level 3 - add
### Difficulty: *
#### Question: There is a file in your folder called `README`, you should add it to your staging area
### Answer: 
```
git add README
```

## Level 4 - commit
### Difficulty: *
#### Question: The `README` file has been added to your staging area, now commit it.
### Answer: 
```
git commit -m "add README file"
```

## Level 5 - clone
### Difficulty: *
#### Question: Clone the repository at https://github.com/Gazler/cloneme.
### Answer: 
```
git clone https://github.com/Gazler/cloneme
```

## Level 6 - clone_to_folder
### Difficulty: *
#### Question: Clone the repository at https://github.com/Gazler/cloneme to `my_cloned_repo`.
### Answer: 
```
git clone https://github.com/Gazler/cloneme my_cloned_repo
```

## Level 7 - ignore
### Difficulty: **
#### Question: The text editor 'vim' creates files ending in `.swp` (swap files) for all files that are currently open.  We don't want them creeping into the repository.  Make this repository ignore those swap files which are ending in `.swp`.
### Answer: 
Add the following text to '.gitignore' in the repository
```
vim .gitignore
--- content
*.swp
---
```

## Level 8 - include
### Difficulty: **
#### Question: Notice a few files with the '.a' extension.  We want git to ignore all but the 'lib.a' file.
### Answer: 
Add the following text to .gitignore` in the repository
```
vim .gitignore
--- content
*.a
!lib.a
---
```
Comment: * means all, ! means exclude

## Level 9 -  status
### Difficulty: *
#### Question: There are some files in this repository, one of the files is untracked, which file is it?
### Answer: 
```
git status
```
Comment: Use git status to track the status of files in current repo 

## Level 10 - number_of_files_committed
### Difficulty: *
#### Question: There are some files in this repository, how many of the files will be committed?
### Answer: 
```
git status
```
Comment: Use git status to track the status of files in current repo 

## Level 11 - rm
### Difficulty: **
#### Question: A file has been removed from the working tree, however the file was not removed from the repository.  Find out what this file was and remove it.
### Answer: 
```
git rm deleteme.rb 
```
or 
```
git add .

```

## Level 12  - rm_cached
### Difficulty: **
#### Question: A file has accidentally been added to your staging area, find out which file and remove it from the staging area.  *NOTE* Do not remove the file from the file system, only from git.
### Answer: 
```
rm --cached "deleteme.rb"
```
Comment: This will move file that staged from staging area to working area

## Level 13  - stash
### Difficulty: **
#### Question: You've made some changes and want to work on them later. You should save them, but don't commit them.
### Answer: 
```
git stash
```
Comment: This will clear working tree and work on them later. This is the functionality of stash

## Level 14  - rename
### Difficulty: ***
#### Question: We have a file called `oldfile.txt`. We want to rename it to `newfile.txt` and stage this change.
### Answer: 
```
git mv "oldfile.txt" "newfile.txt"
```
```
mv oldfile.txt newfile.txt
git add .
```

## Level 15  - restructure
### Difficulty: ***
#### Question: You added some files to your repository, but now realize that your project needs to be restructured.  Make a new folder named `src` and using Git move all of the .html files into this folder.
### Answer: 
```
mkdir src
mv  *.html  src/
git add .
```

## Level 16  - restructure
### Difficulty: ***
#### Question: You added some files to your repository, but now realize that your project needs to be restructured.  Make a new folder named `src` and using Git move all of the .html files into this folder.
### Answer: 
```
mkdir src
mv  *.html  src/
git add .
```



















