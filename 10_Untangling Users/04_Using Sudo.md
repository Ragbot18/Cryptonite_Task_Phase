# Untangling Users
## Using Sudo

### Objective: To learn how to use the sudo command.

Flag: `pwn.college{Yyhmc2AXtcy50h9evJauA3RllHc.QX4UDN1wiM1EzNzEzW}`

```
ls
sudo cat not-the-flag
```

### Solution:

First, listed all the files to find the correct file. Then, used the `sudo` command and printed the flag in the file.

### Incorrect Tangent:

At first, I was trying to run the /challenge/run program which was the incorrect approach.

### What I Learned: 

In the modern world, we have moved on from `su` to `sudo` which is much safer and more convenient.

Using `sudo` we can access only those commands to which we have access to as a specific user.
