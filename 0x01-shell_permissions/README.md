su - switches current user to the other user
whoami - prints username of the current user
groups -prints groups current user is part of
chown - changes the owner of the file
touch - creates an empty file
chmod u+x - execute permissions to the owner of the file
chmod ug+x, o+r - execute permissions to owner of the group, and read permissions to other users
chmod ugo+x - permissions for everyone
chmod 007 - permissions forother users only
chmod 753 -sets mode of the file to info
chmod --reference= - mirror other directory
chmod -R +1111 */ - execute permissions to all subdirectories of the current directory for  users, groups and owner
mkdir -m 751 my_dir - directory permissions
chgrp - change group
