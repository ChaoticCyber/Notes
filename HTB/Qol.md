
Interesting observation where a user upgraded the usability of their shell

```
script -qc /bin/bash /dev/null
[CTRL+Z]

stty raw -echo; fg
			reset xterm


echo $TERM

export TERM=xterm
```


auto