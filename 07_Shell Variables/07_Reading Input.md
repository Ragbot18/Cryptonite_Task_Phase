# Shell Variables
## Reading Input

### Objective: To learn how to read input from the user in Linux terminal.

Flag: `pwn.college{4MoRwp3fyY_h4mr__0uVU-bexxi.QX4cTN0wiM1EzNzEzW}`

```
read -p "Input: " PWN
Input: COLLEGE
```

### Solution:

I used the `read` command with `-p` argument (To give a prompt) to input the value of the `PWN` variable from the user and retrieve the flag.

### What I Learned: 

`read` command is used to take an input from the user.

`read -p` can be used to give a prompt display for the input.