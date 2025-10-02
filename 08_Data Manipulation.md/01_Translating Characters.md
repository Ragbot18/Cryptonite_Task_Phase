# Data Manipulation
## Translating Characters

### Objective: To learn how to translate character using the `tr` command.

Flag: `pwn.college{8Ub6HNAf4sOhBpTvstNUKginj59.01MxEzNxwiM1EzNzEzW}`

```
/challenge/run | tr "a-zA-Z" "A-Za-z"
```

### Solution:

I used the `tr` command on the piped data and converted the lower case characters into upper case and vice versa to retrieve the flag.

### Incorrect Tangent:

At first glance, I thought to swap each character one-by-one which I later realized would be a tedious task. I had to refer online for guidance regarding this shortcut of swapping lowercase and uppercase letters.

### What I Learned: 

`tr` command can be used to translate characters from stdout and then print them.