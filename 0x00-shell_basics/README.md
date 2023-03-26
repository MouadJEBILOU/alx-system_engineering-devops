TASK 0 : Write a script that prints the absolute path name of the current working directory :
#!/bin/bash
pwd

TASK 1 : Display the contents list of your current directory :
#!/bin/bash
ls

TASK 2 : Write a script that changes the working directory to the user’s home directory :
#!/bin/bash
cd ~

TASK 3 : Display current directory contents in a long format :
#!/bin/bash
ls -l

TASK 4 : Display current directory contents, including hidden files (starting with .). Use the long format :
#!/bin/bash
ls -la

TASK 5 : Display current directory contents.
-->Long format
-->with user and group IDs displayed numerically
-->And hidden files (starting with .)
#!/bin/bash
ls -la --numeric-uid-gid
