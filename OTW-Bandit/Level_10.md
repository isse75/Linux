# Level 10

The password for the next level is stored in the file data.txt in one of the few human-readable strings, preceded by several ‘=’ characters.

**Login Details**
```
~ % ssh bandit9@bandit.labs.overthewire.org -p 2220
~ % 4CKMh1JI91bUIZZPXDqGanal4xvAg0JM
```

**Commands**
```
~$ ls
~$ strings data.txt | grep ==
```
Password: FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey

**Commands Used**
- ls: view files in directory
- strings data.txt: return lines of string in the file data.txt
- (.. grep ==): return lines that contain two equalis signs
