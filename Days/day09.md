# Basics of Linux file permission

Linux is a multi-user operating system and it uses the concepts of “ownership” and “permissions” to enhance the security of the files and directories.

Every file and directory on Linux system is owned by a specific user and group. Therefore, file/directory permissions are defined separately for users, groups, and others.

**_User_:** The username of the person who owns the file/directory. By default, the user who creates the file/directory will become its owner.

**_Group_:** The user group that owns the file/directory. All users who belong to the group that owns the file/directory will have the same access permissions to the file/directory.

**_Other_:** A user who isn’t the owner of the file/directory and doesn’t belong to the same group the file/directory does. In other words, if you set a permission for the “other” category, it will affect everyone else by default. For this reason, people often talk about setting the “world” permission when they mean setting the permissions for “other."

If you want to view the users on your system, you can view the /etc/passwd file by running the following command:

<div align="center">
  $ cat /etc/passwd
</div>

Similarly, you can view the groups on your system by viewing the /etc/group file, by running the following command:

<div align="center">
  $ cat /etc/group
</div>

## Linux use 3 types of permissions as follows,
1. Read
2. Write
3. Execute

## Identifying Permissions

r = read permission

w = write permission

x = execute permission

_ = no permission

<p align="center">
<img src="https://github.com/dubeyshubham786/90daysofdevops/blob/main/images/Linux%20file%20access%20permission.png" alt="read write execute" width="100%" height="80%" />
</p>
