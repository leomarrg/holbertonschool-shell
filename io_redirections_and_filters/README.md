This is the documentation for the SHEL I/O redirections and filters

create directory io_redirections_and_filters
create readme file

Exercises:

0. Write a script that prints “Hello, World”, followed by a new line to the standard output. file: 0-hello_world
cmd input:

vim 0-hello_world

chmod u+x 0-hello_world - make file executable
in vim added 
echo "Hello World!"

did git add, commit and push

1. Write a script that displays a confused smiley "(Ôo)'. file: 1-confused_smiley

vim 1-confused_smiley
chmod u+x 1-confused_smiley

add cmd echo -e "\00D4" to output O with ^ on top - just a test to see if it works
git add, commit, push

 cmd echo -e "\"(\00D4o)'"

git add, commit and push

2. Display the content of the /etc/passwd file.

create file - vim 2-hellofile
add exe permissions chmod u+x

cmd cat /etc/passwd

git add, commit, push

3. Display the content of /etc/passwd and /etc/hosts

create file
add exe permissions chmod u+x

cmd cat /etc/passwd /etc/hosts

git add, commit, push


