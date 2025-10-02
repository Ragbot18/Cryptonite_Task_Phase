# Untangling Users
## Becoming Root with su

### Objective: To learn how to become root user with the su command.

Flag: `pwn.college{AEwaoBJoqwMz2_ukWfbGwkAp0s7.QX1UDN1wiM1EzNzEzW}`

```
su
Password: hack-the-planet
cat not-the-flag
```

### Solution:

Used the `su` command to acces the root user terminal and provided it with the correct password. Then, read the file in the root terminal containing the flag.

### What I Learned: 

`su` is an outdated command which requires password to access root user, which is not the method used nowadays.