
`tar czvpf - ./[dir] | gpg --symmetric --no-symkey-cache --cipher-algo aes256 -o [filename]


`gpg -d cs48.tar.gz.gpg | tar -xvzf -`
`