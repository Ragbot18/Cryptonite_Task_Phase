# Untangling Users
## Cracking Passwords

### Objective: Learning how to crack passwords using John the Ripper method.

Flag: `pwn.college{A97Dl5Eut-DiqshTOAOTSwrnWQC.QX3UDN1wiM1EzNzEzW}`

```
john /challenge/shadow-leak
su zardus
Password: aardvark
/challenge/run
```

### Solution:

We used John the Ripper method to decrypt a hashed password and then used that password to access the zardus user. Finally, ran the program in zardus's terminal to retrieve the flag.

### What I Learned: 

Passwords are stored in `/etc/shadow` (leak).
