## Challenge was to list the content of a file with spaces
```bash 
# to complete this challenge i listed the files in the current directory
ls
# i saw the file with spaces name --spaces in filename--
# i used the idea from the previous challenge to try to list the content
cat ./--spaces in this filename--
# but this didn't work, because of the space in the file's name
# we have to make use of escape characters \ to signify the spaces
cat ./--spaces\ in\ this\ filename--
# and i got the password for bandit3
```