## Lab2
### 1. Create a user account with the following attribute and username: islam and Fullname/comment: Islam Askar and Password: islam
![1](https://github.com/menna-abdallah/Linux/assets/139376864/e1ae1a92-b88d-47fb-8493-191ae2392ffc)


### 2. Create a user account with the following attribute and Username: baduser and Full name/comment: Bad User and Password: baduser
![2](https://github.com/menna-abdallah/Linux/assets/139376864/302160fb-cedb-454d-a2bf-544d2cdca979)


### 3. Create a supplementary (Secondary) group called pgroup with group ID of 30000
![3](https://github.com/menna-abdallah/Linux/assets/139376864/2576f01a-0b25-470e-91d6-099bbcf881b2)


### 4. Create a supplementary group called badgroup
![4](https://github.com/menna-abdallah/Linux/assets/139376864/f0230ca5-e27d-4c4e-8017-69ea5de0ff5c)


### 5. Add islam user to the pgroup group as a supplementary group
![5](https://github.com/menna-abdallah/Linux/assets/139376864/ade54603-b50f-4a14-9902-e193102505a7)


### 6. Modify the password of islam's account to password
![6](https://github.com/menna-abdallah/Linux/assets/139376864/407e7aab-87a6-4ec8-8124-7b970fbf5ba3)


### 7. Modify islam's account so the password expires after 30 days
![7](https://github.com/menna-abdallah/Linux/assets/139376864/dcae1a52-6105-41cb-81c6-39f24dec79d0)


### 8. Lock bad user account so he can't log in
![8](https://github.com/menna-abdallah/Linux/assets/139376864/8e2fae30-3759-4dad-bbdc-abd8ad902192)


### 9. Delete bad user account
![9](https://github.com/menna-abdallah/Linux/assets/139376864/fe92918e-aa6a-4d4c-8624-d950ca6e56d6)


### 10. Delete the supplementary group called badgroup.
![10](https://github.com/menna-abdallah/Linux/assets/139376864/7bfbf483-bcb8-4e58-bd06-79b723d54462)


### 11. Create a folder called myteam in your home directory and change its permissions to read only for the owner.
![11](https://github.com/menna-abdallah/Linux/assets/139376864/75fcf44c-cc15-462d-8bc1-ea9cb1d2d2a5)


### 12.Log out and log in by another user
![12](https://github.com/menna-abdallah/Linux/assets/139376864/3e310b5a-4bf1-4f07-aa27-157fe72115c9)


### 13.Try to access (by cd command) the folder (myteam)
![13](https://github.com/menna-abdallah/Linux/assets/139376864/f88a2368-1eee-4201-a793-90cde87600c0)


### 14.Using the command Line
### a) Change the permissions of oldpasswd file to give owner read and write permissions and for group write and execute and execute only for the others (using chmod in 2 different ways).
![14](https://github.com/menna-abdallah/Linux/assets/139376864/8ea017b6-0019-45ea-a835-fb4cbaaf5a8d)
![14-1](https://github.com/menna-abdallah/Linux/assets/139376864/f81b665c-50d7-41c3-9767-469968a512cd)

### b) Change your default permissions to be as above.
![15](https://github.com/menna-abdallah/Linux/assets/139376864/848f0061-fb7e-463f-87d9-06b441a7e070)

### c) What is the maximum permission a file can have, by default when it is just created? And what is that for directory?
#### file >>> 666 >>> rw-rw-rw-
#### directory >>> 777 >>> rwxrwxrwx

### d) Change your default permissions to be no permission to everyone then create a directory and a file to verify.
![16](https://github.com/menna-abdallah/Linux/assets/139376864/296f5550-007c-4e61-8f76-6b7d802776a9)


### 17.What are the minimum permission needed for:
### a) Copy a directory (permission for source directory and permissions for target parent directory)
#### source >>> r--
#### destination >>> -w-

### b) Copy a file (permission for source file and and permission for target parent directory)
#### source file >>> r--
#### source dir >>> --wx
#### destination dir >>> --wx

### c) Delete a file
#### parent dir >>> -wx

### d) Change to a directory
####  source dir >>> -wx
#### destination >>> -wx

### e) List a directory content
#### dir >>> r-x

### f) View a file content
#### dir >>> r--

### g) Modify a file content
#### dir >>> -w-



