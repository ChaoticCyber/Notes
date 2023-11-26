```
Nmap scan report for 192.168.247.250
Host is up (0.045s latency).

PORT      STATE SERVICE       VERSION
135/tcp   open  msrpc         Microsoft Windows RPC
139/tcp   open  netbios-ssn   Microsoft Windows netbios-ssn
445/tcp   open  microsoft-ds?
3389/tcp  open  ssl
|_ssl-date: 2023-11-26T17:23:19+00:00; +1s from scanner time.
|_ssl-known-key: ERROR: Script execution failed (use -d to debug)
| ssl-cert: OpenSSL required to parse certificate.
| -----BEGIN CERTIFICATE-----
| MIIC0jCCAbqgAwIBAgIQb7dHNio1gZ5HI6I5sCReKDANBgkqhkiG9w0BAQsFADAS
| MRAwDgYDVQQDEwdXSU5QUkVQMB4XDTIzMDkyNjAwMzIzM1oXDTI0MDMyNzAwMzIz
| M1owEjEQMA4GA1UEAxMHV0lOUFJFUDCCASIwDQYJKoZIhvcNAQEBBQADggEPADCC
| AQoCggEBAMZUwHgTl79pTItlpe9R3KnwhH0Z22Me1PDqqUWbx3m5lA0P+c8fTrhI
| iA2DiILQ7XCRH/0vKJtDz2X+HsrveZdxuLxlaXyCOZ3XaA3skeaS2xRs68CRmC9E
| O5cNaMJ62Z52jeEJ7F/lZAEpm6nbOI6SdRn4gyZq/DdOvxBMoxPRyBKquakWmvVM
| s3531kRu/w9Wigo+EyaDKxCKahBhT66ID5/WSa0QK357WlrHgHmvtMXipwPqlxpA
| 9zKYTnDA6KszLU2JQmFHkVt4g+dSIp2TZd0lETNl+B9g6yLC5EbDF4qYTdqRUi0P
| f3xQrN7qEmxl+4L0qRY6dEibhuk9JAUCAwEAAaMkMCIwEwYDVR0lBAwwCgYIKwYB
| BQUHAwEwCwYDVR0PBAQDAgQwMA0GCSqGSIb3DQEBCwUAA4IBAQBYtSuRxsuRO/18
| 0mey5K407GjE++Lmj3UlURdprqhmPwX/lkbW9wjfzkKkxuMQQeEqo8sHpOCBJabI
| krsA1yGVVng2e/AcmlhVZLgfuIHoyKJqJIjEbzUZo7UKeqiXVoKM6oQueJqlVco7
| 67O0R8w5wC/IrBd6DpcFIUKI6Gvv23pw+T/FlXlJxHF7tlkaI6MAPeQ7m1sumX91
| lzjugcvAVfV+InmH9J+Qp2JQyGOO3/WY9sDna4Ap+8h+4D5YOebYMLH6sv5s18rg
| bVTsDb1wtyh5k0oRqRYxcEIJFwvHvE+341kS1TZwHHWB2OfhVD115SZWDv4s54r3
| 1UFKAA8L
|_-----END CERTIFICATE-----
5040/tcp  open  unknown
49664/tcp open  msrpc         Microsoft Windows RPC
49665/tcp open  msrpc         Microsoft Windows RPC
49666/tcp open  msrpc         Microsoft Windows RPC
49667/tcp open  msrpc         Microsoft Windows RPC
49668/tcp open  msrpc         Microsoft Windows RPC
49669/tcp open  msrpc         Microsoft Windows RPC
49670/tcp open  msrpc         Microsoft Windows RPC
Warning: OSScan results may be unreliable because we could not find at least 1 open and 1 closed port
Device type: general purpose
Running (JUST GUESSING): Microsoft Windows 11|10 (88%), FreeBSD 6.X (85%)
OS CPE: cpe:/o:freebsd:freebsd:6.2 cpe:/o:microsoft:windows_10
Aggressive OS guesses: Microsoft Windows 11 21H2 (88%), FreeBSD 6.2-RELEASE (85%), Microsoft Windows 10 (85%)
No exact OS matches for host (test conditions non-ideal).
Network Distance: 4 hops
Service Info: OS: Windows; CPE: cpe:/o:microsoft:windows

Host script results:
| smb2-security-mode: 
|   3:1:1: 
|_    Message signing enabled but not required
| smb2-time: 
|   date: 2023-11-26T17:23:05
|_  start_date: N/A

TRACEROUTE (using proto 1/icmp)
HOP RTT      ADDRESS
1   44.12 ms 192.168.45.1
2   44.10 ms 192.168.45.254
3   43.61 ms 192.168.251.1
4   43.70 ms 192.168.247.250

OS and Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 177.57 seconds
```