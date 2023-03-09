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
