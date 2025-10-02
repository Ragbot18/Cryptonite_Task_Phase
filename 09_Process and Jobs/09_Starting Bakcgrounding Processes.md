# Processes and Jobs
## Starting Backgrounding Processes

### Objective: 

Flag: `pwn.college{oWY8dZw30ccpXDdots1bxiOWXtn.QX5QDO0wiM1EzNzEzW}`

```
/challenge/run &
```

### Solution:

Just appended a `&` to the command to directly background the process from the start and retrieve the flag.

### What I Learned: 

We can append a `&` to a command to start it from the background itself.