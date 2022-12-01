su betty - Create a script that switches the current user to the user betty.
 whoami - Write a script that prints the effective username of the current user.
groups - Write a script that prints all the groups the current user is part of.
chown betty hello - Write a script that changes the owner of the file hello to the user betty.
touch hello - Write a script that creates an empty file called hello.
chmod u+x hello - Write a script that adds execute permission to the owner of the file hello.
chmod +114 hello  - Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello. 
chmod +111 hello - Write a script that adds execution permission to the owner, the group owner and the other users, to the file hello
chmod 007 hello - Write a script that sets the permission to the file hello as follows:

Owner: no permission at all
Group: no permission at all
Other users: all the permissions
chmod 753 hello - Write a script that sets the mode of the file hello to this:
#!/bin/bash
chmod --reference=olleh hello - Write a script that sets the mode of the file hello the same as olleh’s mode.

The file hello will be in the working directory
The file olleh will be in the working directory
