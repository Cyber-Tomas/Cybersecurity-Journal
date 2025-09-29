---
tags:
  - linux
  - cml
  - terminal
topic:
  - Bandit Challenge
related:
  - "[[bandit1]]"
  - "[[bandit2]]"
source:
  - overthewire.org
date: 2025-09-24
---
## Challenge was to navigate to another directory and find an hidden file
```bash
# after logging in to bandit3 the first thing i did was to list the things 
# in the home directory using:
ls
# but this time around instead of a file we have a directory
# to enter this directory i used the change directory command
cd <directory name>
# this takes you inside the directory name you entered, then you list the 
# available things in that directory
ls
# we discover that nothing comes up, this means that the file is hidden
# to see hidden files we use the list all option
ls -a
# then we see the hidden file in the directory, and we list the content using
cat ./<hidden file name>
# make sure the dots preceeding the hidden file name is included it is not
# for decoration.
 
```