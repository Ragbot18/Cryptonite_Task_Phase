# Data Manipulation
## Sorting Data

### Objective: To learn how to sort through data using the sort command.

Flag: `pwn.college{8lwV950No0BsDQSW2GPFDuhSz4C.0FM0MDOxwiM1EzNzEzW}`

```
sort /challenge/flags.txt
```

### Solution:

Just sorted the output of `/challenge/flags.txt` alpabetically to retrieve the flag.

### What I Learned: 

`sort` command is used to organize data.

By default, sort orders organizes data alphabetically but different arguments can be provided to manipulate it:

`-r`: reverse order (Z to A) </br>
`-n`: numeric sort (for numbers) </br>
`-u`: unique lines only (remove duplicates) </br>
`-R`: random order