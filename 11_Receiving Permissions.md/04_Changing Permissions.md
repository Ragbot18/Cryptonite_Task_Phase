# Receiving Permissions
## Changing Permissions

### Objective: To learn how to alter permissions for file for specific users and groups.

Flag: `pwn.college{ct-zqJ5eYMSLbocWL-gadm1I6ea.QXzcjM1wiM1EzNzEzW}`

```
chmod a+r /flag
cat /flag
```

### Solution:

Used the `chmod` command with `a+r` argument to give the read permission to all users. Then, read the file to retrieve the flag.


### Incorrect Tangents:

I first tried using `u+r` but it didn't give the permission as the user was root.

### What I Learned: 

`chmod` function can be used to change file permissions. 

Format: `chmod u/a/g/o+rwx filename` 

u: User
a: All Users
g: Group
o: Others
r: Read
w: Write
x: Execute 
a: Append