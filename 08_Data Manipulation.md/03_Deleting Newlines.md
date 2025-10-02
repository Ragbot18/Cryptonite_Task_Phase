# Data Manipulation
## Deleting Newlines

### Objective: To learn about the newline character and how to delete it.

Flag: `pwn.college{kB10j6uN4mngI03wmpYLHkQ6Lzm.0VNxEzNxwiM1EzNzEzW}`

```
/challenge/run | tr -d "\n"
```

### Solution:

I ran the program and used the `tr` command to specifically delete the newline characters `"\n"` and get the flag in a single line.

### What I Learned: 

\n --> Newline Character

\ is itself an escape character. So, `\\` is treated as \ by `tr` as we have to escape \.