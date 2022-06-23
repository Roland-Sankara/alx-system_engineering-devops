# Shell Permissions
This file describes what each script is doing

## 0-My name is Betty
This script changes the current user to betty. It use the `su` command (Switch User) to chancurrent user.

## 1-who_am_i
This script prints the username of the current user. Its uses the `whoami` command to do this.

## 2-groups
This script lists all the groups that the current logged In user belongs to.

## 3-new_owner
This script changes the file owner with the use of the `chown` command.

## 4-empty
This script creates an empty file with the help of the `touch` command.

## 5-execute
This script adds the execute file permission to the hellofile owner. It uses the `chmod` commad to achive that. The options passed are `u+x`: u represent the file owner and +x adds the executes permission.

## 6-multiple_permissions
This script is used to update the hello file permissions for the owner, group and others.

## 7-everybody 
This script gives the owner, group and others execution permission over a file called hello. The command use is `chmod`.

## 8-James_Bond
This script sets all users to have all file permissions while the owner and the group have none

## 9-John_Doe
This script updates a users files permissions using the `chmod` command

## 10-mirror_permissions
This script will update the file mode for hello file with that of olleh. This is done with the `chmod --reference=filename filename`

## 11-directories_permissions
This script will update the permissions of the subfolders. This uses the commsnd `chmod`togther with the `find` command.

## 12-directory_permissions
This script helps to create a directory and them set it's permissions.

## 13-chnage_group
This script changes the group to which the file belongs using the `chgrp` command

## 100-Change_owner_and_group
This script changes the owner and group of all the files and directories in the current working directory. It uses the command `chown -R username:groupname directoryname`

## 101-Symbolic_link_permission
This script chnages the ownership and group of a symbolic link. This by using the `chown -h user:group link`

## 102-if_only
This script will update the file owner only if the current owner is verified. It uses the command `chown --from=current-owner new-owner file`
