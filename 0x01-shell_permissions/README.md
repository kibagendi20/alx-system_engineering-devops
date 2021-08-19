su betty switches the current user to the user betty.
whoami// echo "$USERNAME/USER/ prints the effective username of the current user.
groups - prints all the groups the current user is part of.
sudo chown betty hello changes the owner of the file hello to the user betty.
touch hello - creates empty file called hello
chmod u+x hello adds execute permission to the owner of the file hello.
chmod u+x,g+x,o+r adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
chmod a+x adds execution permission to the owner, the group owner and the other users, to the file hello