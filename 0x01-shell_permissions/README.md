0. su betty: changes the user to betty
1. whoami:  prints the effective username of the current user
2. groups: prints all the groups the current user is part of
3. chown betty hello: changes the owner of the file hello to the user betty
4. touch: it is used to create empty file5. chmod 744 hello : adds execute permission to the owner of the file 
6. chmod 754 hello: adds execute permission to the owner and the group owner, and read permission to other users
7. chmod a+x hello: adds execution permission to the owner, the group owner and the other users, to the file hello
8. chmod 007 hello: sets the permission to the file hello
9. chmod 753 hello: sets the mode of the file hello to -rwxr-x-wx
10. sets the mode of the file hello the same as olleh’s mode
11. chmod a+X * : adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users
12. mkdir -m 751 my_dir : creates a directory called my_dir with permissions 751 in the working directory
13. chgrp school hello : changes the group owner to school for the file hello
