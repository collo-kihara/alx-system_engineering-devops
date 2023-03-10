0-iam_betty switches the current user to betty
1-who_am_i prints the effective username of the current user
2-groups prints all the groups the current user is part of
3-new_owner changes the owner of the file hello to user betty
4-empty creates an empty file hello
5-execute adds execute permission to the owner of hello
6-multiple_permissions adds execute permissions to the owner and group owner, and read permissions to other user for file hello
7-everybody adds execute permission to owner, group owner and other users to file hello
8-James_Bond gives other users all permissions and none to owner and group owner
9-John_Doe gives owner all permissions, read and execute to group owner and write and execute permissions to other users
10-mirror_permissions gives hello same permissions as olleh
11-directories_permissions adds execute permissions to all subdirectories of the working directory for all users
12-directory_permissions creates a directory my_dir with mode 751
13-change_group changes group owner to school for file hello
100-change_owner_and_group changes owner of all files and directories to vincent and group owner staff
101-symbolic_link_permissions changes owner and group owner of _hello to vincent and staff
103-Star_Wars plays StarWars IV in the terminal