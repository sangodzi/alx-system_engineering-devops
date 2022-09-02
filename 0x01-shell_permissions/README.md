Shell Permissions: This folder contains script with bash commands to create, manipulate and update file permissions of owner, group and other users on various files and directories.

## Name: 0-iam_betty

   This script switches the current user to betty

## Name: 1-who_am_i

   This script prints the effective username of the current user.

## Name: 2-groups

   This script prints all the groups the current user is part of.

## Name: 3-new_owner

   This script changes the owner of the file hello to the user betty

## Name: 4-empty

   This script creates an empty file called hello.

## Name: 5-execute

   This script adds execute permission to the owner of the file hello.

## Name: 6-multiple_permissions

   This script adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

## Name: 7-everybody

   This script adds execution permission to the owner, the group owner and the other users, to the file hello.

## Name: 8-James_Bond

   This script sets the following permissions to the file hello:
   1. Owner: no permission at all
   2. Group: no permission at all
   3. Other users: all the permissions
   It's a double zero seven magic, if you know what I mean!

## Name: 9-John_Doe

   This script sets the mode of the hello to -rwxr-x-wx

## Name: 10-mirror_permissions

   This script mirrors the file permission of a file named olleh to a file named hello.

## Name: 11-directories_permissions

   This script adds execute permission to all subdirectories of the current diretory that begins with 'dir' for the owner, the group owner and all other users.

## Name: 12-directory_permission

   This scripts creates a new directory called my_dir with permissions: drwxr-x--x in the working directory.

## Name: 13-change-group

   This script changes the group owner to school for the file hello.

## Name: 100-change_owner_and_group

   This script changes the owner to vincent and group owner to staff for all files and directories.

## Name: 101-symbolic_link_permissions

   This script changes the owner and group owner of a symbolic link referenced file

## Name: 102-if_only

   This script changes the owner of the file if only it is owned by a specified user

## Name: 103-Star_Wars

   This script connects to telnet and plays the StarWars IV episode in the terminal.
   