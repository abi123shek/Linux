# 5. User Management

## how do you create a new user in linux?
```bash sudo adduser username```
## how do you delete a user?
```bash sudo userdel username```
## how do you lock a user aacount?
```bash sudo passwd -l username```
## how do you unlock a user account?
```bash sudo passwd -u username```
## how do you switch to another user?
```bash su - username```
## how do you view currently logged-in users?
```bash who or w```
## how do you check user account infromation?
```bash id username```
## how do you list all users on the system?
```bash cat /etc/passwd```
## how do you create a group in linux?
```bash groupadd group_name```
## how do you add a user to a group?
```bash usermod -aG group_name username```
## how do you change a user's default shell?
```bash chsh -s /bin/bash username```
## how do you change a user's home directory?
```bash usermod -d /new/home/dir username```
## how do you create a system user without a home directory?
```bash adduser --system --no-create=home username```
## how do you set or reset a user's password?
```bash passwd username```
## how do you check group memberships of a user?
```bash groups username```












