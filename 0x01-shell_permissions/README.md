Creating shell permissions scripts
0. The 0-iam_betty script switches the current to the user 'betty.'
1. The 1-who_am_i script prints the effective username of the current user.
2. The 2-groups script prints all the groups the user is part of.
3. The 3-new_owner script changes the ownership of the 'hello' file to 'betty.'
4. The 4-empty script creates a new empty file called 'hello.'
5. The 5-execute script adds execute permission to the owner if the 'hello' file.
6. The 6-multiple_permissions script adds execute permission to the owner and the group owner, and read permissionto other users, to the 'hello' file.
7. The 7-everybody script adds execution permission to everyone.
8. The 8-James_Bond removes every permission for the owner and owner groups of the 'hello' file and grants full permissions to other users.
9. The 9-John_Doe script changes the hello file permissions to -rwxr-x-wx.
10. The 10-mirror_permissions script mirrors the user permissions of another file.
11. The 11-directories_permissions script adds executive permission to bevery subdirectory in the working directory.
12. The 12-directory_permissions scrpt creates the my_dir with a permission.
13. The 13-change_group script changes the hello file's group owner to 'school.'
14. The 100-change_owner_and_group script changes the owner and group names for all the files and subdirectories in the current working folder to vincent and staff respectively.
15. The 101-symbolic_link-permissions changes the ownerand group owner names of the symbolic link _hello to vincent and staff respectively.
16. The 102-if_only script changes the the owner of the 'hello' file to betty if only the owner's name is guillaume.
17. the 103-Star_Wars script plays the StarWars episode IV in the terminal.
