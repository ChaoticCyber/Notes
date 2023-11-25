Enable RDP
```
shell reg add "HKLM\SYSTEM\CurrentControlSet\Control\Terminal Server" /v fDenyTSConnections /t REG_DWORD /d 0 /f

shell netsh advfirewall firewall set rule group="remote desktop" new enable=Yes




shell reg add "HKEY_LOCAL_MACHINE\System\CurrentControlSet\Control\Lsa" /v DisableRestrictedAdmin /t REG_DWORD /d 0 /f
```