# Processes and Jobs
## Foregrounding Processes

### Objective: To learn how to foreground processes already running in the background of the terminal.

Flag: `pwn.college{Imb5F5ZfviY9zQBpKPBz0HYDVvN.QX4QDO0wiM1EzNzEzW}`

```
/challenge/run
^Z
bg /challenge/run
fg /challenge/run
```

### Solution:

First, I ran the program and suspended it. Then, resumed the program in the background using `bg` command and finally foregrounded the program from the background using `fg` command to retrieve the flag.

### What I Learned: 

We can foreground a background process using `fg` command.
