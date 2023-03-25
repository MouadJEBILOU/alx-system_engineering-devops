# alx-system_engineering-devops

TASK 0 : Create a script that switches the current user to the user betty :
#!/bin/bash
su betty

TASK 1 : Write a script that prints the effective username of the current user :
#!/bin/bash
echo $USER

TASK 2 : Write a script that prints all the groups the current user is part of :
#!/bin/bash
groups $USER

TASK 3 : Write a script that changes the owner of the file hello to the user betty :
#!/bin/bash
chown betty hello

TASK 4 : Write a script that creates an empty file called hello :
#!/bin/bash
touch hello

TASK 5 : Write a script that adds execute permission to the owner of the file hello :
#!/bin/bash
chmod u+x hello

TASK 6 : Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello :
#!/bin/bash
chmod u+x,g+x,o+r hello
