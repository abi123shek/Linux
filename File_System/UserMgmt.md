# 5. User Management

## how do you create a new user in linux?
``` sudo adduser username```
## how do you delete a user?
``` sudo userdel username```
## how do you lock a user aacount?
``` sudo passwd -l username```
## how do you unlock a user account?
``` sudo passwd -u username```
## how do you switch to another user?
``` su - username```
## how do you view currently logged-in users?
``` who or w```
## how do you check user account infromation?
``` id username```
## how do you list all users on the system?
``` cat /etc/passwd```
## how do you create a group in linux?
``` groupadd group_name```
## how do you add a user to a group?
``` usermod -aG group_name username```
## how do you change a user's default shell?
``` chsh -s /bin/bash username```
## how do you change a user's home directory?
``` usermod -d /new/home/dir username```
## how do you create a system user without a home directory?
``` adduser --system --no-create=home username```
## how do you set or reset a user's password?
``` passwd username```
## how do you check group memberships of a user?
``` groups username```












