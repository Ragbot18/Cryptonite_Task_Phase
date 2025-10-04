# Chaining Commands
## Handling Failure

### Objective: To learn about the OR operator in the terminal.

Flag: `pwn.college{YR7i7wF5r4B6fe7Iop0BroAWd7U.01M0MDOxwiM1EzNzEzW}`

```
/challenge/first-failure || /challenge/second
```

### Solution:

- Used `||` to chain the commands so it executes even if the command fails.

### What I Learned: 

- `||` is used to chain commands.

- `||` is like the `OR` operator. If the first command executes successfully, the second command is not executed and it only runs the second command if the first command fails.
