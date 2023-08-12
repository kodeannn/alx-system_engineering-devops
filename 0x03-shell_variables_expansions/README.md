alias ls="rm*" - command that creates an alias
echo "hello $USER" - a command that prints hello user, and user should display the current linux user instead of just the words user
export PATH=$PATH:/action - makes /action the last directory shell looks into when looking for a program and this is achieved by adding /action to the PATH
echo $((`echo $PATH | grep -o ":/" | wc -l`+ 1)) - commnad that counts the number of directories in the PATH
printenv - lists environment variables
set - a commmand that lists all local variables environment vsrisbles and functions
