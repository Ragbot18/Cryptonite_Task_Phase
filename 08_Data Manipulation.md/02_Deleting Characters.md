# Data Manipulation
## Deleting Characters

### Objective: 

Flag: `pwn.college{sSwZeb4mbD4i_TzgjXlXc8uLyre.0FNxEzNxwiM1EzNzEzW}`

```
/challenge/run | tr -d "^ %"
```

### Solution:

I executed the program and used the `tr` command on the output to delete unwanted characters `^` `%` and retrieve the flag.

### What I Learned: 

We can use `tr -d` to delete specific characters from the stdout.