# Shell Variables
## Storing Command Output

### Objective: To learn about command substitution.

Flag: `pwn.college{8aLSphJ96MHBYu5tSmx8DmiDLVr.QX1cDN1wiM1EzNzEzW}`

```
PWN=$(/challenge/run)
echo $PWN
```

### Solution:

First, I assigned the output of `/challenge/run` command to the variable `PWN`. Then, printed the `PWN` variable to retrieve the flag.

### What I Learned: 

We can use `Var=$(Command)` to assign output of a command to a variable.