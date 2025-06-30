# Level 9

The password for the next level is stored in the file data.txt and is the only line of text that occurs only once

**Login Details**
```
~ % ssh bandit8@bandit.labs.overthewire.org -p 2220
~ % dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc
```

**Commands**
```
~$ ls
~$ sort data.txt | uniq -u

```
Password: 4CKMh1JI91bUIZZPXDqGanal4xvAg0JM

**Commands used**
- ls
- sort data.txt: sorts lines in data.txt file in alphabetical order
- sort data.txt | uniq -u: only returns lines in data.txt file that are unique

