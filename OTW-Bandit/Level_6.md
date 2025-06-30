# Level 6

The password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties:

human-readable
1033 bytes in size
not executable

**Login Details**
```
~$ ssh bandit5@bandit.labs.overthewire.org -p 2220
~$ 4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
```

**Commands**
```
~$ ls
~$ cd inhere
~/inhere$ find . -readable
~/inhere$ find . -readable -size 1033c
~/inhere$ cat ./maybehere07/.file2 -A
```
Password: HWasnPhtq9AVKe0dmk45nxy20cvUa6EG

**Commands Used**
- ls: View all files in directory
- cd inhere: Change Directory, open the inhere folder
- find . -readable: Find all files in directory that are humanly readable
- find . -readable -size 1033c: Find all files in directory that are humanly readable AND 1033 bytes in size
- cat ./maybehere07/.file2 -A: View contents of file
