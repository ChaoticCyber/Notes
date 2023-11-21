
`tar czvpf - ./[encdir] | gpg --symmetric --no-symkey-cache --cipher-algo aes256 -o [filename].tar.gz.gpg`


`gpg -d [decryptfilename] | tar -xvzf -`