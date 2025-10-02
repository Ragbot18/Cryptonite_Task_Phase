# Data Manipulation
## Extracting the First Lines using Head

### Objective: To learn how to use the head command.

Flag: `pwn.college{onRa2JrDFGGzJVUHPmzscvRcHz2.0lNxEzNxwiM1EzNzEzW}`

```
/challenge/pwn | head -n 7 | /challenge/college
```

### Solution:

I first used the `head` command on the stdout of `/challenge/pwn` to filter out the first 7 lines and then gave that as stdin to `/challenge/college` program to retrieve the flag.

### What I Learned: 

`head` command is used to read through the first few lines of its input.

By default, it reads the first 10 lines of the input.