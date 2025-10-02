# Processes and Jobs
## Resuming Processes

### Objective: To learn how to resume processes running in the background of the terminal.

Flag: `pwn.college{ITY7dp0c6A-prxKecB2wVl_6Y-B.QX2QDO0wiM1EzNzEzW}`

```
/challenge/run
^Z
fg /challenge/run
```

### Solution:

First, I ran the program and then suspended the process. Finally, resumed the process using `fg` command to retrieve the flag.

### What I Learned: 

`fg` command is used to resume processes running in the background.


