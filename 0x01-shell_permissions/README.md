# 0x01-shell_permissions

## 0x01. Shell, Permissions

This directory contains my work for 0x01. Shell, Permissions

### Contents

0. A script that switches the current user to the user ```betty``` (0-iam_betty)

    The conditions are:

    * To use exactly 8 characters for the command.
    * Assume that the user ```betty``` will exist when script runs.

1. A script that prints the effective username of the current user (1-who_am_i)

2. A script that prints all the groups the current user is a part of (2-groups)

3. A script that changes the owner of the file ```hello``` to the user ```betty``` (3-new_owner)

4. A script that creates an empty file called ```hello``` (4-empty)

5. A script that adds execute permission to the owner of the file ```hello```. The file is in the working directory (5-execute)

6. A script that adds execute permission to the owner and the group owner, and read permission to other users to the file ```hello```. The file is in the working directory (6-multiple_permissions)

7. A script that adds execution permission to the owner and other users, to the file ```hello``` (7-everybody)

8. A script that gives the other users all the permissions while giving the owner and group none to the file ```hello``` (8-James_Bond)

9. A script that gives the owner all permissions, the group read and execute permissions and the others write and execute permissions to the file ```hello``` (9-John_Doe)

10. A script that sets the mode of the file ```hello``` the same as ```olleh```'s (10-mirror_permissions)

11. A script that adds the execute permission to all subdirectories of the curretn directory for the owner, group owner and all other users. Regular files should not be changed (11-directories_permissions)
