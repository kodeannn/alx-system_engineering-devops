su betty - command used to change from curret user to user betty
whoami - is a command used to print the username of the current user
groups - a command used to shwo the groups the current is part of
sudo chown betty hello - command used to change file ownership from hello to betty
touch hello - creates an empty file called hello
chmod u+x hello - command used to add execute permission to the owner of the file in the working directory, so u refers to the owner of the file while x adds the execute permission
chmod ug+x,o+r hello - command that adds execute permissions to owner of file and group owner (ug+x) and also adds read permissions to other users o+r to the file hello
chmod ugo+x hello - command that adds execution permissions yo all users
chmod o+rwx hello - command that gives other users all the permissions
chmod 007 hello - command that gives only the other users permissions
chmod u=rwx,g=rx,o=wx hello - u=rwx: This sets the permissions for the owner (u) to read, write, and execute (rwx).g=rx: This sets the permissions for the group (g) to read and execute (rx).o=wx: This sets the permissions for other users (o) to write and execute (wx).
chmod 753 hello - (task 9)
chmod --reference=olleh hello - (task 10)
chmod -R +x . - (task 11) 
