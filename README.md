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
```
Add the following text to .gitignore` in the repository

vim .gitignore
--- content
*.swp
---
```

## Level 8 - ignore
### Difficulty: **
#### Question: The text editor 'vim' creates files ending in `.swp` (swap files) for all files that are currently open.  We don't want them creeping into the repository.  Make this repository ignore those swap files which are ending in `.swp`.
### Answer: 
```
Add the following text to .gitignore` in the repository

vim .gitignore
--- content
*.swp
---
```












