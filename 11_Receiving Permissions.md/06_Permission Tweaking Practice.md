# Receiving Permissions
## Permission Tweaking Practice

### Objective: To practice the usage of `chmod` command.

Flag: `pwn.college{I2F7x_emtQZUCBf_U-MNNfi9lmc.QXwEjN0wiM1EzNzEzW}`

```
/challenge/run
chmod o+w /challenge/pwn
chmod u-rw /challenge/pwn
chmod a-rw /challenge/pwn
chmod a+rw /challenge/pwn
chmod u-r /challenge/pwn
chmod o+x /challenge/pwn
chmod g-rw,o-rwx /challenge/pwn
chmod u-w /challenge/pwn
chmod a+r /flag
cat /flag
```

### Solution:

- The challenge required us to execute 8 steps of `chmod` command on the file `/challenge/pwn` consecutively:

    1. Give write access to others.
    2. Remove read and write access from the user.
    3. Remove read and write access from all users.
    4. Give read and write access to all users.
    5. Remove read access from the user.
    6. Give execute access to others.
    7. Remove read and write access from the group and remove read, write and execute access from others.
    8. Remove write access from the user.

- Then, I changed the permission of `/flag` file so we can read it.
- Finally, read the file to retrieve the flag.

