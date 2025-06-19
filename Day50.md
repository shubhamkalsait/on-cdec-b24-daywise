Basic Linux Commands
Redirector
Editor VIM
pipe output
SEDt
AWK
ECHO
SORT
UNIQ
ALIAS

Variables
EXPORT
UNSET
Read/Write from terminal

Conditions

Loops


---------------

uname - kernel
lscpu - 
free -h
df -hT
cat /etc/os-release
date 
echo $SHELL

Redirector
-----------------
direct the output of the terminal

1. >  - output redirect and replace data
2. >> - data append
3. &> - Error and Output file 
4. 2> - Error to file

------------


Q. display top 5 highly utilized disk
df -ht | awk '{print $4, $1}' | sort -r | grep -v 'Used' | head -5 

