TASK 0 : Write a script that prints “Hello, World”, followed by a new line to the standard output :
#!/bin/bash
echo "Hello, World"

TASK 1 : Write a script that displays a confused smiley "(Ôo)' :
#!/bin/bash
echo -e "\"(Ôo)'"

TASK 2 : Display the content of the /etc/passwd file :
#!/bin/bash
cat /etc/passwd

TASK 3 : Display the content of /etc/passwd and /etc/hosts :
#!/bin/bash
cat /etc/passwd /etc/hosts

TASK 4 : Display the last 10 lines of /etc/passwd :
#!/bin/bash
tac /etc/passwd | head | tac
