# 2.File Permissions and Ownership

## how do you change file permissions?
```bash chmod permissions filename```
## how do you change file ownership?
```bash chown user:group filename```
## how do you view file permission in a directory?
```bash ls -l```
## how do you recursively change permissions for a directory?
```bash chmod -R permissions directory_name```
## what does chmod 777 commnad do?
Provide Read, Write Execute permission to everyone
## how do you view a file's access control list (ACL)?
```bash getfacl filename```
## how do you set a default ACL for a directory?
```bash setfacl -d -m u:user:permissions directory_name```
## how do you set permissions for a script to be executable?
```bash chmo +x script.sh```
## what is the significance of the **sticky bit** in linux?
it restricts file deletion in shared directories like /tmp.
## how do you add the sticky bit to a directroy?
```bash chmod +t directory_name

