su : to switch user to the super user betty.
id -un : ti print the effective username of current user.
groups :prints all the groups the current user is part of.
sudo chown betty hello : changes the file hello ownership.
touch
chmod u+x hello:adds execute permission to the owner of the file hello.
chmod ug+x,o+r hello:adds execute permission to the owner and the group owner while adds read permission to other users.
chmod ugo+x hello: adds execute permission to the owner,group owner and other users.
chmod 007 hello: adds all permissions to only the other users.
chmod 753 hello :adds all permissions to the owner while read and excuete permission to the group owner and write and execute to other users.
chmmod --reference=olleh hello:copies olleh file permissions to the hello file.
chmod -R -x .: adds the execute permission to all over the current working directory.
