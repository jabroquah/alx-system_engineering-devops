# 0x01 Shell permissions

The projects in this repository were created specifically for the system engineering devops tasks at ALX.


## Environment

- OS: Ubuntu 20.04.5 LTS
- Language(s): Bash 5.0.17(1)-release

## Files

| File name | Description |
| --------- | ----------- |
| [`0-iam_betty`](https://github.com/jabroquah/alx-system_engineering-devops/blob/main/0x01-shell_permissions/0-iam_betty) | A script that switches the current user to the user `betty` |
| [`1-who_am_i`](https://github.com/jabroquah/alx-system_engineering-devops/blob/main/0x01-shell_permissions/1-who_am_i) | A script that prints the effective username of the current user |
| [`2-groups`](https://github.com/jabroquah/alx-system_engineering-devops/blob/main/0x01-shell_permissions/2-groups) | A script that prints all the groups the current user is part of |
| [`3-new_owner`](https://github.com/jabroquah/alx-system_engineering-devops/blob/main/0x01-shell_permissions/3-new_owner) | A script that changes the owner of the file `hello` to the user `betty` |
| [`4-empty`](https://github.com/jabroquah/alx-system_engineering-devops/blob/main/0x01-shell_permissions/4-empty) | A script that creates an empty file called `hello` |
| [`5-execute`](https://github.com/jabroquah/alx-system_engineering-devops/blob/main/0x01-shell_permissions/5-execute) | A script that adds execute permission to the owner of the file `hello` |
| [`6-multiple_permissions`](https://github.com/jabroquah/alx-system_engineering-devops/blob/main/0x01-shell_permissions/6-multiple_permissions) | A script that adds execute permission to the owner and the group owner, and read permission to other users, to the file `hello` |
| [`7-everybody`](https://github.com/jabroquah/alx-system_engineering-devops/blob/main/0x01-shell_permissions/7-everybody) | A script that adds execution permission to the owner, the group owner and the other users, to the file `hello` |
| [`8-James_Bond`](https://github.com/jabroquah/alx-system_engineering-devops/blob/main/0x01-shell_permissions/8-James_Bond) | A script that sets the permission to the file `hello` as follows: no permission at all for `owner`, `group`. Other users have all the permissions |
| [`9-John_Doe`](https://github.com/jabroquah/alx-system_engineering-devops/blob/main/0x01-shell_permissions/9-John_Doe) | A script that sets the mode of the file `hello` to `rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello` |
| [`10-mirror_permissions`](https://github.com/jabroquah/alx-system_engineering-devops/blob/main/0x01-shell_permissions/10-mirror_permissions) | A script that sets the mode of the file `hello` the same as `olleh`'s mode |
| [`11-directories_permissions`](https://github.com/jabroquah/alx-system_engineering-devops/blob/main/0x01-shell_permissions/11-directories_permissions) | A script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users |
| [`12-directory_permissions`](https://github.com/jabroquah/alx-system_engineering-devops/blob/main/0x01-shell_permissions/12-directory_permissions) | A script that creates a directory called `my_dir` with permissions 751 in the working directory |
| [`13-change_group`](https://github.com/jabroquah/alx-system_engineering-devops/blob/main/0x01-shell_permissions/13-change_group) | A script that changes the group owner to `school` for the file `hello` |
| [`100-change_owner_and_group`](https://github.com/jabroquah/alx-system_engineering-devops/blob/main/0x01-shell_permissions/100-change_owner_and_group) | A script that changes the owner to `vincent` and the group owner to `staff` for all the files and directories in the working directory |
| [`101-symbolic_link_permissions`](https://github.com/jabroquah/alx-system_engineering-devops/blob/main/0x01-shell_permissions/101-symbolic_link_permissions) | A script that changes the owner and the group owner of `_hello` to `vincent` and `staff` respectively |
| [`102-if_only`](https://github.com/jabroquah/alx-system_engineering-devops/blob/main/0x01-shell_permissions/102-if_only) | A script that changes the owner of the file `hello` to `betty` only if it is owned by the user `guillaume` |
| [`103-Star_Wars`](https://github.com/jabroquah/alx-system_engineering-devops/blob/main/0x01-shell_permissions/103-Star_Wars) | A script that will play the StarWars IV episode in the terminal |

## Author

Joseph Abroquah
