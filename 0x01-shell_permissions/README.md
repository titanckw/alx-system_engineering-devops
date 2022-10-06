su betty - creates a script that switches the current user to the user betty
whoami - creates a script that prints the effective username of the current user
groups - creates a script that prints all the groups of the current user is part of
chown betty hello - creates a scripts that changes the owner of the file 'hello' to betty
touch hello - creates a script that creates an empty file called 'hello'
chmod u+x hello - creates a script that adds execute permisison to the owner of the file 'hello'
chmod ug+x,o+r hello - a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
chmod ug+x,o hello - creates a script that adds execution permission to the owner, the group owner and the other users, to the file hello
chmod 007 - creates a script that sets the permission to the file hello as follows:
 Owner: no permission at all
 Group: no permission at all
 Other users: all the permission
chmod 753 hello - Write a script that sets the mode of the file hello to -rwxr-x-wx
chmod --reference=olleh hello - Write a script that sets the mode of the file hello the same as olleh’s mode
sudo chmod -r +111 */ -Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed
mkdir -m 751 my_dir - Create a script that creates a directory called my_dir with permissions 751 in the working directory..  
