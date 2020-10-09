# javiEagleLibs
## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [links](#links)

## General info
My personal eagle libs

	
## Technologies
Project is opened with:
* Eagle
	
## Setup
how to init repo from eagle libraries folder.
https://docs.github.com/en/free-pro-team@latest/github/importing-your-projects-to-github/adding-an-existing-project-to-github-using-the-command-line
https://github.com/chiengineer/Eagle-Libraries/wiki/Configuring-Git-and-Eagle-PCB-Editor

```
#find your libraries directory mine in windows is /mnt/c/Users/Javier/Documents/eagle/libraries
$ cd /mnt/c/Users/Javier/Documents/eagle/libraries

#initialice that folder as a git repo and add all files
$ git init
$ git add .

#make first local commit and link it with the remote repo
$ git commit -m "First commit"
$ git remote add origin https://github.com/javiBajoCero/javiEagleLibs.git
#verifies everything went ok
$ git remote -v


```

## links
https://www.diymodules.org/download/eagle-libs/usr/1012211566/conv/con-3m-skt-header.lbr
