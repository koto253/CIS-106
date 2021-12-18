# Managing Users and Groups
## Managing User Accounts
![userAccount](imgs7/userAccount.png)
   *  How do I add a user in Ubuntu?
      *  Run the command **sudo adduser** followed by the **username**.
   *  How do I delete a user in Ubuntu?
      *  To delete a user use the **userdel -r** command followed by the **username**.
         *  The **-r** option for the command to delete the user and its home directory.

![managingUser](imgs7/managingUser.png)
   *  Understanding the purpose of these files is canonical to the understanding of how users and groups work on in Linux.
      *  /etc/default/useradd
      *  /etc/passwd
      *  /etc/group ...

## The /etc/login.defs file
   *  It contains directives for use in various **shadow password suite commands**.
   *  **Shadow password suite** is an umbrella term for commands dealing with account.
      *  > grep -ve ^$ /etc/login.defs | grep -v ^#

![loginDefs](imgs7/loginDefs.png)

## Creating a user with useradd
![useradd](imgs7/userAdd.png)
* **-md** are the options needed for adding a home directory to the new user.
* **-s** used for specifying the users login shell.

## Maintaining Passwords
![passwords](imgs7/passwords.png)

## Deleting User Accounts
![deleting](imgs7/deleting.png)

## Managing Groups
![group](imgs7/group.png)

## Delete me
![delete](imgs7/delete.png)

## Bash Aliases
![aliases](imgs7/aliases.png)
