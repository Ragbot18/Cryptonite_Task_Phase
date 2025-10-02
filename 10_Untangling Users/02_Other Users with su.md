# Untangling Users
## Other Users with su

### Objective: To learn how to switch to users other than root using the su command.

Flag: `pwn.college{ESl5rbX1zs7MJ6nkbCVueqA7Jmd.QX2UDN1wiM1EzNzEzW}`

```
su zardus
Password: dont-hack-me
/challenge/run
```

### Solution:

Used the su command to switch to `zardus` user using already provided password. Then, ran the program to retrieve the flag.

### What I Learned: 

Arguments can be given to `su` command to access different users.
