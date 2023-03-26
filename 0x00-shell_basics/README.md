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

TASK 5 : Display current directory contents :
-->Long format
-->with user and group IDs displayed numerically
-->And hidden files (starting with .)
#!/bin/bash
ls -la --numeric-uid-gid

TASK 6 : Create a script that creates a directory named my_first_directory in the /tmp/ directory :
#!/bin/bash
mkdir /tmp/my_first_directory

TASK 7 : Move the file betty from /tmp/ to /tmp/my_first_directory :
#!/bin/bash
mv /tmp/betty /tmp/my_first_directory/

TASK 8 : Delete the file betty :
--> The file betty is in /tmp/my_first_directory
#!/bin/bash
rm /tmp/my_first_directory/betty

TASK 9 : Delete the directory my_first_directory that is in the /tmp directory :
#!/bin/bash
rm -r /tmp/my_first_directory

TASK 10 : Write a script that changes the working directory to the previous one :
#!/bin/bash
cd $OLDPWD
