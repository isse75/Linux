# File 11

The password for the next level is stored in the file data.txt, which contains base64 encoded data


**Login Details**
```
~ % ssh bandit10@bandit.labs.overthewire.org -p 2220
~ % FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey
```

**Commands**
```
~$ ls
~$ cat data.txt | base64 -d
```
Password: dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr

**Commands Used**
- ls: view files in directory
- cat data.txt | base64 -d: decode the input in the file from base64 to it's original form
