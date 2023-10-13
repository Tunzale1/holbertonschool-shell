0) *su betty* - switches the current user to the user betty
1) *whoami* - prints the effective username of the current user
2) *groups* - prints all the groups the current user is part of
3) *chown* - changes the owner
4) *touch* - creates a file
5) *chmod u+x, chmod 777* - adds execute permission to the owner of the file
6) *chmod u+x,g+x,o+r* - adds execute permission to the owner and the group owner, and read permission to other users, to the file
7) *chmod ugo+x* - adds execution permission to the owner, the group owner and the other users, to the file
8) *chmod 007* - sets the permission to the file => Owner: no permission at all, Group: no permission at all, Other users: all the permissions
9) *chmod 753* - sets the mode of the file
10) *chmod $(stat -c %a olleh)* -  sets the mode of the file the same as olleh’s mode
11) *chmod a+X ** - adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users
12) *mkdir -m 751 my_dir* - creates a directory called my_dir with permissions 751 in the working directory
13) *chgrp* - changes the group owner
14) *chown -R* - changes the owner and the group owner for all the files and directories in the working directory.
15) *chown -h* - changes the owner and the group owner respectively
16) *chown --from=guillaume vincent hello* - changes the owner of the file hello to vincent only if it is owned by the user guillaume
