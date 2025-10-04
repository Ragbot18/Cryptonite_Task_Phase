# Receiving Permissions
## Fun with Group Names

### Objective: To learn how to combine the use of id and chgrp commands to retrieve the flag.

Flag: `pwn.college{8AbvAmUnNLqKyROtIYf4zx1zlK5.QXycjM1wiM1EzNzEzW}`

```
id
ls
chgrp grp12342 not-the-flag
cat not-the-flag
```

### Solution:

- First, I used `id` command to find the group which the user `hacker` belongs to. 

- Then, listed the files to find the file containing the flag. 

- Then changed the group to `grp12342` for the file and finally read the file to retrieve the flag.

### What I Learned: 

Generally in Linux, every user has their own group, but this is not mandatory.