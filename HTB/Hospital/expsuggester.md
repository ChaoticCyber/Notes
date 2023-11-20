```
msf6 post(multi/recon/local_exploit_suggester) > exploit 

[*] 10.10.11.241 - Collecting local exploits for x64/windows...
[*] 10.10.11.241 - 188 exploit checks are being tried...
[+] 10.10.11.241 - exploit/windows/local/bypassuac_dotnet_profiler: The target appears to be vulnerable.
[+] 10.10.11.241 - exploit/windows/local/bypassuac_sdclt: The target appears to be vulnerable.
[+] 10.10.11.241 - exploit/windows/local/bypassuac_sluihijack: The target appears to be vulnerable.
[+] 10.10.11.241 - exploit/windows/local/cve_2020_1048_printerdemon: The target appears to be vulnerable.
[+] 10.10.11.241 - exploit/windows/local/cve_2020_1337_printerdemon: The target appears to be vulnerable.
[+] 10.10.11.241 - exploit/windows/local/cve_2022_21882_win32k: The target appears to be vulnerable.
[+] 10.10.11.241 - exploit/windows/local/cve_2022_21999_spoolfool_privesc: The target appears to be vulnerable.
[+] 10.10.11.241 - exploit/windows/local/ms16_032_secondary_logon_handle_privesc: The service is running, but could not be validated.
[*] Running check method for exploit 45 / 45
[*] 10.10.11.241 - Valid modules for session 6:
============================

 #   Name                                                           Potentially Vulnerable?  Check Result
 -   ----                                                           -----------------------  ------------
 1   exploit/windows/local/bypassuac_dotnet_profiler                Yes                      The target appears to be vulnerable.
 2   exploit/windows/local/bypassuac_sdclt                          Yes                      The target appears to be vulnerable.
 3   exploit/windows/local/bypassuac_sluihijack                     Yes                      The target appears to be vulnerable.
 4   exploit/windows/local/cve_2020_1048_printerdemon               Yes                      The target appears to be vulnerable.
 5   exploit/windows/local/cve_2020_1337_printerdemon               Yes                      The target appears to be vulnerable.
 6   exploit/windows/local/cve_2022_21882_win32k                    Yes                      The target appears to be vulnerable.
 7   exploit/windows/local/cve_2022_21999_spoolfool_privesc         Yes                      The target appears to be vulnerable.
 8   exploit/windows/local/ms16_032_secondary_logon_handle_privesc  Yes                      The service is running, but could not be validated.

```