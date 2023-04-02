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

TASK 5 : Display the first 10 lines of /etc/passwd :
#!/bin/bash
head -n 10 /etc/passwd

TASK 6 : Write a script that displays the third line of the file iacta :
#!/bin/bash
head -n 3 iacta | tail -n 1

TASK 7 : 

TASK 8 : Write a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it : 
#!/bin/bash
ls -la > ls_cwd_content

TASK 9 : Write a script that duplicates the last line of the file iacta :
#!/bin/bash
tail -n 1 iacta >> iacta

TASK 10 : Write a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders : 
#!/bin/bash
find . -type f -name "*.js" -delete

TASK 11 :

TASK 12 : Create a script that displays the 10 newest files in the current directory : 
#!/bin/bash
ls -1t | head -10

TASK 13 : Create a script that takes a list of words as input and prints only words that appear exactly once : 
#!/bin/bash
sort | uniq -u

TASK 14 : Display lines containing the pattern “root” from the file /etc/passwd :
grep "root" /etc/passwd

TASK 15 : Display the number of lines that contain the pattern “bin” in the file /etc/passwd :
#!/bin/bash
grep -c "bin" /etc/passwd

TASK 16 : Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd :
grep -A 3 "root" /etc/passwd

TASK 17 : 