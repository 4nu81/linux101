#### Users and Permissions

* /etc/passwd
* /etc/group
* /etc/shadow

```bash
adduser username # interactively create a user (Debian)
addgroup groupname # create a group (Debian)
adduser username groupname (Debian)
useradd -opts username # create a user (Unix standard, non-interactive)
usermod -opts username # manipulate group membership, user attributes
chown username path # change owner for path
chgrp groupname path # change group for path
```


#### File permissions and `chmod`
<img src="images/lsperms.png">

```bash
chmod ugo+r foo # grant READ permissions for everyone
chmod -R o-rwx  foo # remove all permissions for others, recursively
chmod ug+x foo # grant EXECUTE for owner and group
find . -type d -exec chmod g+s {} \;  # set SGID for all folders under pwd
```


Octal Representation
<img src="images/octalperms.png">
```bash
chmod 644 foo # set u=rw,g=r,o=r 
chmod 2755 foo # set u=rwx,g=rs,o=rx
```
