```id``` - print UID and GID 
```sudo id``` - print UID and GID supper user
```useradd -m -s /bin/bash user_name``` - create user
```adduser user_name``` - script for create user
```groupadd group_name``` - create group
```addgroup group_name``` - create group
```passwd``` - change self password
```passwd user_name``` - change password for select user
```usermod -aG group_name user_name``` - add user in group
```chown user_name:group_name file_name``` - change owner and group
```chgrp group_name file_name``` - change group
```su user_name``` - switch user
```visudo``` - edit sudoers
```sudoedit /etc/sudoers``` - edit sudoers
```userdel [-r] user_name``` - remove user
