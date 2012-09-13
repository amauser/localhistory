localhistory
============

Bash history that is local to the directory.

Every command you type in the shell will be stored in a local file
".history-${USER}" with a timestamp. 

This is great for check later, what you did and re-using old commandlines.
Having this per user also allows you to check, what other users have done in
that directory.

Installing: 

source bash_localhistory from this repository in your .bash_profile or .bashrc
... you are good to go!

Using:

There are some convenience functions defined to let you access the local
history:

h                gives you the last 10 commands executed in the local 
                 directory
gh <pattern>     greps the local history for <pattern>



