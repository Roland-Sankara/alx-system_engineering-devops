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
