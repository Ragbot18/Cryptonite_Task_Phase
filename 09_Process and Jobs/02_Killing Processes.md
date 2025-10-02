# Processes and Jobs
## Killing Processes

### Objective: To learn how to kill processes in the terminal.

Flag: `pwn.college{gLPIPgr4T95zbRGXPu369GXl_yV.QXyQDO0wiM1EzNzEzW}`

```
ps -ef
kill 137
/challenge/run
```

### Solution:

I started with listing all the process in full format and then found the PID for the `/challenge/dont_run` program. Then, I killed the program and executed `/challenge/run` program to retrieve the flag.

### What I Learned: 

`kill` command is used to kill processes. We have to provide the PID of the process we want to end.
