pwd- prints the path of current working directory
ls- prints all files in directory
cd ~ - used to navigate to the home directory
ls -l - used to list files in working directory in long format
ls -la - used to list all files in working directory even hidden ones
ls -lna - used to list files in long format, (n)with user and group IDs displayed numerically and (a)hidden files
mkdir /tmp/my_first_directory - used to make a directory inside another directory
mv /tmp/betty /tmp/my_first_directory - used to move a file to a directory inside another directory
rm /tmp/my_first_directory/betty - used to delete the file betty which is in the directory /tmp/my_first_directory
rmdir /tmp/my_first_directory - used to delete a directory thats inside another directory
cd - - changes the working directory to the previous one
ls -la . .. /boot - used to list files in long format, hidden files in the current directory which is represented with a . and the parent directory represented with a .. and the /boot directory
file /tmp/iamafile - used to show what type of file iamafile is which is in directory /tmp
ln -s /bin/ls __ls__ - used to create a symbolic link in the current working directory, which will point to the /bin/ls executable
cp -u *.html .. - used to copy files which are new or do not exist in the destination directory (u) and the files should be ending with .html and they should be in the parent directory rep by (..)
mv [A-Z]* /tmp/u/ - used to move all files beginning with an uppercase ([a-z]) to the directory /tmp/u
rm *~ - used to delete all files in current working directory that end with the character ~
mkdir -p welcome/to/school - used to create the directories welcome, to , and school
ls -amvp - explain later
echo '0 string SCHOOL School data file' > school.mgc && file -C -m school.mgc - explain later
