TASK 0 : Write a script that prints the absolute path name of the current working11;rgb:0000/0000/0000directory :
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
cd -

TASK 11 : Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format :
#!/bin/bash
ls -la . .. /boot

TASK 12 : Write a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script :
#!/bin/bash
file /tmp/iamafile

TASK 13 : Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory :
#!/bin/bash
ln -s /bin/ls __ls__

TASK 14 : Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
You can consider that all HTML files have the extension .html :
#!/bin/bash
cp -u -- *.html ..

TASK 15 : Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u :
#!/bin/bash
mv [A-Z]* /tmp/u
