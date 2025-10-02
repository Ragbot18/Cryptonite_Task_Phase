# Data Manipulation
## Extracting Specific Sections of Text

### Objective: To learn how to use the cut command to extract specific sections of data.

Flag: `pwn.college{8zEmG892u_FtwiM3-hfvV8KuC0k.01NxEzNxwiM1EzNzEzW}`

```
/challenge/run | cut -d " " -f 2 | tr -d "\n"
```

### Solution:

Firstly, I gave the stdout of `/challenge/run` to the `cut` command to extract the second column of each line (each character of the flag) and then used the `tr` command to delete the newline characters and print the flag in a single line.

### What I Learned: 

The `cut` command is used to grab specific columns of data.

The -d argument specifies the column delimiter, how the columns are to be separated.

The -f argument specifies the column number to extract.