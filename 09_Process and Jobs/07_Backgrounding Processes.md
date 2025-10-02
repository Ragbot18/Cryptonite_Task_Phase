# Processes and Jobs
## Backgrounding Processes

### Objective: To learn how to resume processes in the background.

Flag: `pwn.college{Ib-lH5ZQuQ_BTTmmmrB_Twk0Jk4.QX3QDO0wiM1EzNzEzW}`

```
/challenge/run
^Z
bg /challenge/run
/challenge/run
```

### Solution:

Started with running the program and suspending it immediately after. Then, resumed the process in the background using `bg` command and then finally ran the program again to retrieve the flag.

### What I Learned: 

`bg` command is used to resume processes in the background of the terminal.