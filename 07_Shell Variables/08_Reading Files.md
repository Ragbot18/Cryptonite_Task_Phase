# Shell Variables
## Reading Files

### Objective: To learn how to use the read command to read files.

Flag: `pwn.college{8HuvQ7yTrsN3YKxJXQrAWzG4vKB.QXwIDO0wiM1EzNzEzW}`

```
read PWN < /challenge/read_me
```

### Solution:

Used the `read` command and redirected the stdout of `/challenge/read_me` to the variable `PWN` to retrieve the flag.

### What I Learned: 

`read` command can also take redirected stdout of files as argument and assign it to a variable. This can be used to read files in the shell.