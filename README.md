# >
You can redierect output using ">" after a command to create and save the output file.
ex) ls -lh > file_list.txt
#cat
displays the content of a text file
ex) cat file_list.txt
# >>
Using ">>" appends output to an extising file or create and write to a new file if it doesn't exist.
standard input
you can redierect input from a file using "<".
You can use "<"and">" together for store new txt.

# pipelines "|"
pipelines feeds output of previous command to input of next command.
ex)command1|command2|command3|....

# Expansion
Special characters expand its meaning when given to shell commands.
ex) echo * , ~
##backslash 
backslah can be used to ignore line cahnge in command("enter"),
to enter a long command in multiple lines.

# permissions
Files and directories have a permission assigned differently to owner/group/other.
-rwx/rwx/rwx
 -:file, d:directory, r:read , w:write, x:execute
 
 chmod: changes permissions
 ex) chmod 600 some_file 
 
 ```
 6=110=rw- for owner  
 0=000=--- for group 
 0=000=--- for others 
 rwx = 111 =7 
 r-x = 101 =5 
 r-- = 100 =4 
 ```
 
 # Superuser
 A speruser has all system administation authority.
 Some commands need superuser's privilleges.
 put "sudo" before the command if you are a superuser.
 ex) sudo some_command
 "exit" to get out of a superuser session.
 
 # text Editors
 ```
vi,vim 
Emacs
nano
gedit
kwrite
```

# shell script
write and run a shell script.
 
 
 
 
 
