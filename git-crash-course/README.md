## Git Hidden Folder

There is a hidden fodler called `.git` which tells you that our project is a git repo.

If we wanred to create a git repo in a new project we create the folder and the initalize that repo  using `git init`



```sh
mkdir /worksapce/tmp/new-project
cd /worksapce/tmp/new-project
git init
touch README.md
vi README.md
#Make changes to readme.md file
git add README.md
git commit -m "add readme file"
```


## Cloning 

We can clone three ways: HTTPS, SSH, Github CLI.

Since we are using GitHUB codespaces we'll create a tmp directory in our workspace.

```sh
mkdir /workspace/tmp
cd /workspace/tmp
```


## HTTPS 

```sh
git clone https://github.com/Bryan-Cortes/Github-Example.git
```



## Commits

When we want to commit code we can write git commit which will open up the commit edit message in the editor of choice. 

```sh
git commit -m
```

## Branches

## Stashing

## Merging

## Add

When we want to stage changes that will be included in the commit
We can use the . to add all possibles files. 

```sh
git add README.md
git add .
```
## Status

Git status shows you what files will or will not be comitted. 


```sh
git status
```

## Reset 

Reset allows you to move Staged changes to be unstaged.
This is useful when you want to revert all files not be commiteed.

```sh
git add .
git reset
```

