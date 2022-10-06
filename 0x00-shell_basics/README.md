0-current_working_directory: the script is "pwd" and it prints the absolute path name of the current working directory.
1-listit: the script is "ls" and it displays the content list of your current directory.
2-bring_me_home: the script is "cd" and it changes the working directory to the user’s home directory.
3-listfiles: the script is "ls -l" and it displays current directory contents in a long format.
4-listmorefiles: the script is "ls -l -a" and it displays current directory contents, including hidden files using the long format.
5-listfilesdigitonly: the script is "ls -na" and it displays current directory contents.
6-firstdirectory: the script is "mkdir /tmp/my_first_directory" and it creates a directory named my_first_directory in the /tmp/ directory.
7-movethatfile: the script is "mv /tmp/betty /tmp/my_first_directory
" and it moves the file betty from /tmp/ to /tmp/my_first_directory.
8-firstdelete: the script is "rm /tmp/my_first_directory/betty
" and deletes the file betty.
9-firstdirdeletion: the script is "rm -rf /tmp/my_first_directory/" and it deletes the directory my_first_directory that is in the /tmp directory.
10-back: the script is "cd" and it changes the working directory to the previous one.
11-lists: the script is "ls -la . .. /boot" and it  lists all files in the current directory and the parent of the working directory and the /boot directory in long format.
12-file_type: the script is "file /tmp/iamafile" and it prints the type of the file named iamafile.
13-symbolic_link: the script is "ln -s /bin/ls __ls__" and it creates a symbolic link to /bin/ls and link should be created in the current working directory.
14-copy_html: the script "cp -un *.html ../" and it creates a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory. 
