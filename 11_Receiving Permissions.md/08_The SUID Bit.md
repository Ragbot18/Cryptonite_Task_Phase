# Receiving Permissions
## The SUID Bit

### Objective: To learn about SUID permission used to give owner access to particular files.

Flag: `pwn.college{IOM68QWaS9Ev2P3F-2s71OTkQm4.QXzEjN0wiM1EzNzEzW}`

```
chmod u+s /challenge/getroot
/challenge/getroot
cat /flag
```

### Solution:

- First, used the `chmod` command to add SUID to `/challenge/getroot`.

- Then, ran the program as the owner.

- Finally, read the `/flag` file to retrieve the flag.

### What I Learned: 

We can add SUID access to a file which lets us open the file as the owner of the file. This can be done by running `u+s`.