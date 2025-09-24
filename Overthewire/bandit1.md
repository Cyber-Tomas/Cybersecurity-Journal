## Challenge was to find the password in bandit1 for bandit2
```bash
# in level one of the bandit, the password is kept in a file named -
# i used the same command as before 
cat - # but this did not work because linux sees it as an option not a filename
# the first method i used was to check the current directory i was in
pwd 
# it printed /home/bandit1/, so i ran 
cat /home/bandit1/- 
# telling linux to list the content of - in the /home/bandit1 directory
# another method is to use
cat ./-
# ./ tells linux that whatever comes after is in the current directory
```