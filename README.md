Shell permissions Task Repo in github

0. My name is Betty
mandatory
Create a script that switches the current user to the user betty.

You should use exactly 8 characters for your command (+1 character for the new line)
You can assume that the user betty will exist when we will run your script

1. Who am I
mandatory
Write a script that prints the effective username of the current user.

2. Groups
mandatory
Write a script that prints all the groups the current user is part of.

3. New owner
mandatory
Write a script that changes the owner of the file hello to the user betty.

4. Empty!
mandatory
Write a script that creates an empty file called hello.

5. Execute
mandatory
Write a script that adds execute permission to the owner of the file hello.

6. Multiple permissions
mandatory
Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

7. Everybody!
mandatory
Write a script that adds execution permission to the owner, the group owner and the other users, to the file hello

8. James Bond
mandatory
Write a script that sets the permission to the file hello as follows:
Owner: no permission at all
Group: no permission at all
Other users: all the permissions

9. John Doe
mandatory
Write a script that sets the mode of the file hello to this:
-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello

10. Look in the mirror
mandatory
Write a script that sets the mode of the file hello the same as olleh’s mode.

11. Directories
mandatory
Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
Regular files should not be changed.

12. More directories
mandatory
Create a script that creates a directory called my_dir with permissions 751 in the working directory.

13. Change group
mandatory
Write a script that changes the group owner to school for the file hello

14. Owner and group
advanced
Write a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.

15. Symbolic links
advanced
Write a script that changes the owner and the group owner of _hello to vincent and staff respectively.
The file _hello is in the working directory
The file _hello is a symbolic link

16. If only
advanced
Write a script that changes the owner of the file hello to betty only if it is owned by the user guillaume.

17. Star Wars
advanced
Write a script that will play the StarWars IV episode in the terminal.
