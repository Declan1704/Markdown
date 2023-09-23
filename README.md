# COMMANDS ABOUT GROUP IN LINUX
## Introduction
![image](https://github.com/Declan1704/Markdown/assets/145857414/906a8f19-83d5-48b0-b268-a84ec013760f)

Here after typing the command, the yellow line shows the user name and the red mark shows the group name. Since it is the home directory, the user and group name is same.
## 1)Command that shows which group my user is a member of:
`$ groups`
## 2) Command that shows which group another is a member of
`$ groups <username>`

**Here the username is the name of the user you've created**
## 3)  Command to List of all the groups of a special file
`cat /etc/group`

**There are several separated in a colon. The first column tells the name of the group. The second column is the password. The next column is the group GID(same as UID).
## 3)Command to create a group
`$ sudo groupadd <groupname>

**Here the group name can be any name of your choice.
## 3)Command to delete a group
`$ sudo groupdel <groupname>
# Types of Groups
## 1) Primary Group


After
