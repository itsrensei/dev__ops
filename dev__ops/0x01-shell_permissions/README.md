0x01. Shell, permissions

Script
0-iam_betty
Description: a script that switches the current user to the user betty.

1-who_am_i
Description: this is a script that prints the effective username of the current user.
using the whoami command, although id -un can also be used

2-groups
Description: This script prints all the groups the current user is part of.

3-new_owner
Description: a script that changes the owner of the file hello t another user.

4-empty: ascript that created an empty file with the name hello

5-execute: Added a file that gives the user permission to execute a file

6-multiple_permissions: a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello

7-everybody:a script that that adds execution permission to the owner, the group owner and the other users, to the file hello.

8-James_Bond: a script that gives full permissions to other and none to user and group

9-John_Doe: this is a script that sets the hello file to give full permission to the user, read and execute for group and write and execute for other.

10-mirror_permissions: this is a script that references its permissions from another file.
