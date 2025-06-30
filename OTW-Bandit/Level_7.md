# Level 7

The password for the next level is stored somewhere on the server and has all of the following properties:

owned by user bandit7
owned by group bandit6
33 bytes in size

**Login Details**
```
~ % ssh bandit6@bandit.labs.overthewire.org -p 2220
~ % HWasnPhtq9AVKe0dmk45nxy20cvUa6EG
```

**Commands**
```
~$ ls -A
~$ find / -type f -size 33c -user bandit7 -group bandit6
~$ find / -type f -size 33c -user bandit7 -group bandit6 2>/dev/null
~$ cat /var/lib/dpkg/info/bandit7.password
```
Password: morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj

**Commands Used**
- ls -A: view viles in directory
- find /: find files in root directory
- find / -type f -size 33c -user bandit7 -group bandit6: find files in root directory that's 33 bytes, belongs to user bandit7 and group bandit6
- (.. 2>/dev/null): Only show files that are eligible
- cat /var/lib/dpkg/info/bandit7.password: View file contents
