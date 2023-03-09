# Mar 9th, 2023 Tasks: [0x01-shell-permissions]

- My name is Betty 

	- Command `su` to switch user

- Who am i

	- Command `whoami` to check current user name

- Groups

	- Command `groups` to display current user's groups

- Change owner

	- Command `chown <user> <file>` to change the owner of file/directory

- Empty!

	- Command `touch` to create a new emtpy file

- Execute

	- Command `chmod u+x <file>` to allow file execution by owner

- Multiple permissions 

	- Command `chmod ug+x,o+r <file>` to allow file execution by owner and group

- Everybody! 

	- Command `chmod a+x <file>` to allow file execution by everybody

- James Bond 

	- Command `chmod 007 <file>` to allow all permission by others only

- John Doe

	- Command `chmod 753 <file>` to set permission to -rwxr-x-wx

- Look in the mirror
	
	- Command `chmod --reference=<ref_file> <file>` to copy permissions from reference file

- Directories

	- Command `chmode -R a+X *` to set execute permission to sub-directories of the current directory for all users

- More directories 

	- Command `mkdir -m 751 my_dir` create a directory called my_dir with 751 permission

- Change Group

	- Command `chown :<group> <file>` to change target file/directory group owner

- Owner and group

	- Command `chown <user>:<group> <file>` to change user and group of a file/directory

- Symbolic link

	- Command `chown <user>:<group> -h <link_file>` to change user and group owner of a symbolic link

- If only

	- Command `chown --from=<target_user> <new_user> <file>` to change the user of files with some username

- Star Wars

	- Command `telnet <address>` to connect to remote host using telnet
