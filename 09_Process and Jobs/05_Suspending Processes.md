# Processes and Jobs
## Suspending Processes

### Objective: To learn how to suspend processes to the background.

Flag: `pwn.college{8qf_abF09D7S9_HDiFJlJZ9MBf8.QX1QDO0wiM1EzNzEzW}`

```
/challenge/run
^Z
/challenge/run
```

### Solution:

The challenge required me to first run the program, then suspend it to the background and run it again to retrieve the flag. This had to be done as the flag would only be given if the program has 2 copies running in the terminal.

### What I Learned: 

We can use `Ctrl+Z` to suspend processes to the background.
