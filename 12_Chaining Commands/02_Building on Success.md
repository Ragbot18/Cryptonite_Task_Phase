# Chaining Commands
## Building on Success

### Objective: To learn about the AND operator in the terminal.

Flag: `pwn.college{s5Qcb72xWAUuzw2wWHMzDsqwsnD.0lM0MDOxwiM1EzNzEzW}`

```
/challenge/first-success && /challenge/second
```

### Solution:

- Running `/challenge/first-success` gives no output. 

- Running `/challenge/second` shows an error saying that it needs to be chained with `&&` to work.

- Used `&&` to chain the commands `/challenge/first-success` and `/challenge/second` which only executes the second command if the first one doesn't give an error.

### What I Learned: 

- `&&` can be used to chain commands.

- It works as `AND` operator as it only executes the second command if the first one is successfully executed.