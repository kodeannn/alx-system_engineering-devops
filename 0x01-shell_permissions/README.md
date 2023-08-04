su betty - command used to change from curret user to user betty
whoami - is a command used to print the username of the current user
groups - a command used to shwo the groups the current is part of
sudo chown betty hello - command used to change file ownership from hello to betty
touch hello - creates an empty file called hello
chmod u+x hello - command used to add execute permission to the owner of the file in the working directory, so u refers to the owner of the file while x adds the execute permission
chmod ug+x,o+r hello - command that adds execute permissions to owner of file and group owner (ug+x) and also adds read permissions to other users o+r to the file hello
