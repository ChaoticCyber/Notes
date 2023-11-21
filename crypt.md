
`tar czvpf - ./[encdir] | gpg --symmetric --no-symkey-cache --cipher-algo aes256 -o [filename]`


`gpg -d [decrypt] | tar -xvzf -`