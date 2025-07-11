# Level 12

The password for the next level is stored in the file data.txt, where all lowercase (a-z) and uppercase (A-Z) letters have been rotated by 13 positions

**Login Details**
```
~ % ssh bandit11@bandit.labs.overthewire.org -p 2220
~ % dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr
```

**Commands**
```
~$ ls -a
~$ cat data.txt | tr 'N-ZA-Mn-za-m' 'A-Za-z'

```
The password is 7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4

**Commands Used**
- ls -a
- cat data.txt
- tr 'N-ZA-Mn-za-m' 'A-Za-z' -> Decode ROT13 Text
