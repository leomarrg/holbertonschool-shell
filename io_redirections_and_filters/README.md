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

Write a script that displays a confused smiley "(Ôo)'. file: 1-confused_smiley

vim 1-confused_smiley
chmod u+x 1-confused_smiley

add cmd echo -e "\00D4" to output O with ^ on top - just a test to see if it works
git add, commit, push

edit cmd echo -e "("\00D4"o)"
