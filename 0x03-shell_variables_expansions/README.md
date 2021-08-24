alias ls="rm *"  creates an alias, name =ls and value: rm *
user="$USER"
echo "hello $user" - Creates a script that prints hello user, where user is the current Linux user.
export PATH=$PATH:/action - Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
echo $((`echo $PATH | grep -o ":/" | wc -l`+ 1)) - counts the number of directories in the PATH.
printenv - lists environment variables.