level01:

`cat /etc/passwd | grep flag01`

```Output
flag01:42hDRfypTqqnw:3001:3001::/home/flag/flag01:/bin/bash
```
(apt install john)
$ echo 42hDRfypTqqnw > file
$ /usr/sbin/john ./file
Loaded 1 password hash (descrypt, traditional crypt(3) [DES 128/128 SSE2])
Will run 8 OpenMP threads
Press 'q' or Ctrl-C to abort, almost any other key for status
abcdefg          (?)
1g 0:00:00:00 100% 2/3 33.33g/s 1092Kp/s 1092Kc/s 1092KC/s 123456..thebest3
Use the "--show" option to display all of the cracked passwords reliably
Session completed

$ /usr/sbin/john --show ./file 
?:abcdefg

1 password hash cracked, 0 left

$su flag01

f2av5il02puano7naaf6adaaf
