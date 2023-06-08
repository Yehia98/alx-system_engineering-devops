su : to switch user to the super user betty.
id -un : ti print the effective username of current user.
groups :prints all the groups the current user is part of.
sudo chown betty hello : changes the file hello ownership.
touch
chmod u+x hello:adds execute permission to the owner of the file hello.
chmod ug+x,o+r hello:adds execute permission to the owner and the group owner while adds read permission to other users.
chmod ugo+x: adds execute permission to the owner,group owner and other users.
