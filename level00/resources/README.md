level00:

Find file from user (ommit warnings):
`find / -user flag00 2>/dev/null`

```Output
/usr/sbin/john
/rofs/usr/sbin/john
```

Get the file contents:
`cat /usr/sbin/john`

```Output
cdiiddwpgswtgt
```

Solve with rot11, get `notttoohardhere`.
$su flag00

x24ti5gi3x0ol2eh4esiuxias

