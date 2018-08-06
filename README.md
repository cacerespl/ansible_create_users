# ansible_create_users

## Create users on a group of Linux servers and force them to change the password when login for the first time.

1) Generate a hashed password with: **openssl passwd -1**

2) Create a file **user.yml** that contains the variables (users and hashed password)

3) Create the file **create_user.yml**, that perform two tasks:
   - Create a group of users
   - Force the user to change the password when login for the first time 

4) Run the playbook: **ansible-playbook create_user.yml** 


