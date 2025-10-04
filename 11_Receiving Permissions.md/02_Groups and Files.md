# Receiving Permissions
## Groups and Files

### Objective: To learn about users and groups in the terminal and how to change groups.

Flag: `pwn.college{c5rMhbRRhxhSsuDnAILhLZIuvBa.QXxcjM1wiM1EzNzEzW}`

```
ls
chgrp hacker not-the-flag
cat not-the-flag
```

### Solution:

- First, I listed all the files to look for the file contaning the flag `not-the-flag`.
- Then, changed the group of the file to `hacker` so that we can access it as the user `hacker`. 

- Finally, read the file to retrieve the flag.

### What I Learned: 

`chgrp` command is used to change groups of files. It can generally only be accessed by the `root` user.

`id` command can be used to gain information about a user (like its group ID etc.)

