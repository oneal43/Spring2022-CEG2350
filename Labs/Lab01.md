## Lab 01

- Name: Michael O'Neal
- Email: oneal.43@wright.edu

## Part 1 Answers

1. mkdir DirA
2. mkdir 'Dir B'
3. cd 'Dir B'
4. DirB is a better naming convention because it lessens the probability that the user will type the directory mname incorrectly. 
5. mv 'Dir B' DirB

## Part 2 Answers

1. cd DirA > vim test.txt
2. File contents:

```
This is the first line of text.
This is the second line of text.
This is the third line of text.
```

## Part 3 Answers

1. cp test.txt .hiddentext.txt
2. ls -lah

## Part 4 Answers

1. sudo adduser bob
2. /home/bob
3. No. The gorup that I belong to has read only access.
4. su bob > enter password
5. cd ..
6. Yes. Bob has read and write access
7. su moneal > enter password
8. Confirmed location using pwd. Had I not been in the home directory already, I would have used cd .. to back uo to the home directory.

## Part 5 Answers

1. sudo addgroup crew > enter password for moneal
2. sudo usermod -a -G crew moneal and sudo usermod -a -G crew bob
3. sudo chgrp -R crew DirA
4. su bob > enter password (had to change permissions for group by signing back in as moneal and using chmod 775 DirA to enable write access for the gorup bob belongs to. 
5. vim file.txt
6. Bob had full read, write, and execute privaleges since the group he belongs to was given full access.

## Part 6 Answers

1. sudo vim sudowho.txt
2. -rw--r--r
3. W10: Warning: Changing a read only file

## Extra Credit

1.
2.
3.
