# Processes and Jobs
## Killing Misbehaving Processes

### Objective: To kill misbehaving processes which are sending decoy flags to the file and retrieve the correct flag.

Flag: `pwn.college{gk3wJt1DIzkCzBRUZqFRL37ODC7.0FNzMDOxwiM1EzNzEzW}`

```
ps -ef
kill 142
/challenge/run
cat /tmp/flag_fifo
```

### Solution:

First, I listed all the ongoing processes in full format. Then, I searched through the processes to find the misbehaving process which is sending decoy flags to our file. I then proceeded to use the PID of the process to kill it. Then, I ran the program and read the file to retrieve the flag.




