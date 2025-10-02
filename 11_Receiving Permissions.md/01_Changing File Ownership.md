# Receiving Permissions
## Changing File Ownership

### Objective: To learn how to change file ownership.

Flag: `pwn.college{ofYNBbI2xjQme4PdSOzmwhhpzY5.QXxEjN0wiM1EzNzEzW}`

```
chown hacker /flag
cat /flag
```

### Solution:

Just changed the ownership of `/flag` file to the user `hacker` and then read the file to retrieve the flag.

### What I Learned: 

`chown` command can be used to change ownership of file from one user to another. Generally, only `root` user has access to this command.