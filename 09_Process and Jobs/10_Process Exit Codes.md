# Processes and Jobs
## Process Exit Codes

### Objective: To learn how to access exit codes of processes.

Flag: `pwn.college{Ip4lfwH5uJRMIRepPPvZXq9L5Gm.QX5YDO1wiM1EzNzEzW}`

```
/challenge/get-code
echo $? /challenge/get-code
/challenge/submit-code 162
```

### Solution:

First, I executed the `/challenge/get-code` program so it can exit with the code. Then, printed that code using `$?` and finally used that code as argument to `/challenge/submit-code` and retrieved the flag.

### What I Learned: 

We can use `echo $?` to access the exit code of programs. 

Generally, successful commands return 0 and failed commands return 1.
