pwd - The script that prints the absolute path name of the current working directory.
ls - Display the contents list of your current directory.
cd - changes the working directory to the user’s home directory.
ls -l Display current directory contents in a long format
ls -la Display current directory contents, including hidden files (starting with .). Use the long format.
mkdir /tmp/my_first_directory - creates a directory named my_first_directory in the /tmp/ directory.
mv /tmp/betty /tmp/my_first_directory - Move the file betty from /tmp/ to /tmp/my_first_directory.
rm /tmp/my_first_directory/betty - Delete the file betty.
rm -r /tmp/my_first_directory - Delete the directory my_first_directory that is in the /tmp directory.
cd -changes the working directory to the previous one.
ls -la. ../boot/ -  lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format
cp -u *.html .. Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
file /tmp/iamafile - prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.
ln -s /bin/ls __ls__ creates symbolic link to /bin/ls, named __ls__, it's created in the current directory
ls -la Display current directory contents with user and group IDs displayed numerically And hidden files (starting with .)
mv [[:upper:]]* /tmp/u moves all files beginning with an uppercase letter to the directory /tmp/u.
rm *~  deletes all files in the current working directory that end with the character ~.
mkdir -p welcome/to/school creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory
ls -mpa - lists all the files and directories of the current directory, separated by commas (,).