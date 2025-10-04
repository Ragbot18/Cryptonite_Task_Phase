# Receiving Permissions
## Permissions Setting Practice

### Objective: To learn about `=` functionality in `chmod` command.

Flag: `pwn.college{4qcycCxpOnbTlbF9114sph-L0KF.QXzETO0wiM1EzNzEzW}`

```
/challenge/run
chmod u=wx,g=wx,o=rx /challenge/pwn
chmod u=r,g=rx,o=wx /challenge/pwn
chmod u=r,g=w,o=wx /challenge/pwn
chmod u=rx,g=r,o=rw /challenge/pwn
chmod u=rwx,g=w,o=x /challenge/pwn
chmod u=x,g=w,o=x /challenge/pwn
chmod u=r,g=rw,o=rwx /challenge/pwn
chmod u=w,g=x,o=rw /challenge/pwn
chmod a+r /flag
cat /flag
```

### Solution:

Similar to the last challenge, we have to consecutively execute 8 commands to manipulate file permissions and retrieve the flag.

### What I Learned: 

`=` can be used to set the file permission to a particular setting instead of giving or removing access.