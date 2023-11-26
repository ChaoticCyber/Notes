```
Nmap scan report for 192.168.247.248
Host is up (0.048s latency).

PORT      STATE SERVICE       VERSION
80/tcp    open  http          Microsoft IIS httpd 10.0
| http-methods: 
|_  Potentially risky methods: TRACE
|_http-title: Home
| http-robots.txt: 16 disallowed entries (15 shown)
| /*/ctl/ /admin/ /App_Browsers/ /App_Code/ /App_Data/ 
| /App_GlobalResources/ /bin/ /Components/ /Config/ /contest/ /controls/ 
|_/Documentation/ /HttpModules/ /Install/ /Providers/
135/tcp   open  msrpc         Microsoft Windows RPC
139/tcp   open  netbios-ssn   Microsoft Windows netbios-ssn
445/tcp   open  microsoft-ds?
3389/tcp  open  ms-wbt-server Microsoft Terminal Services
| ssl-cert: OpenSSL required to parse certificate.
| -----BEGIN CERTIFICATE-----
| MIIC1DCCAbygAwIBAgIQNIUE1oNUOb1CFhC3GjPOkjANBgkqhkiG9w0BAQsFADAT
| MREwDwYDVQQDEwhFWFRFUk5BTDAeFw0yMzA5MjYwMzQ2MTFaFw0yNDAzMjcwMzQ2
| MTFaMBMxETAPBgNVBAMTCEVYVEVSTkFMMIIBIjANBgkqhkiG9w0BAQEFAAOCAQ8A
| MIIBCgKCAQEA2l/M+IgS+d35D0Mv71nc7KdxqZI6YcN025mPu8asHw8pVpkQ/hXz
| 6kvpzhPUcL3YR2WAYFI7YZUboeYREhuhivG2iCa1FsMvPLVu2JFE25Zt5h/13Zxf
| LT3p+Uz6KNffHMwPHetwLyQDcAHpi5zfSEjJ0zHSCZmK3ZaW0FWbquBX5xVV0Kbc
| vIroU0gS7Gu7CGAUETAOfVcZsMcvYIQaZNjc0Yxx+NXGClJSVzt1htFJWlGibsex
| fIrcguCsXVrqt26+BrGqfghYzTOQ01rZ1FNFxoIUfSBEUozZAfv6EXEjyiFudvsX
| PQESPiI/hS4Sfm7Sew+Qb4NHmhQlU9eNKQIDAQABoyQwIjATBgNVHSUEDDAKBggr
| BgEFBQcDATALBgNVHQ8EBAMCBDAwDQYJKoZIhvcNAQELBQADggEBAK+XWZLcqigs
| x4fq34yxwV/lHAhmL6a5pQn5nsl/6E+F2P/nvDLCVfNmkaLHmZLYQE8F9S1LV0aG
| f84UrMXpo1Q6Md/zrW4JOkBlRRngxXxCJKZT3h8kmflSNLCID6ViXTALHtMNDIp+
| ehJHhozXBLEDKzeMylpie/YwIBcmFLM3nJhwQ182XaCIVeAcsOFia6hBMEkRlc0U
| fDUVfQSNEn5J9XRL7AGKxGtJpHr+raEFvoh/NEOFOseScFDyBRf3d3nSo9bUgnW1
| Ls5ewsvMe+eSX4DRDGmMZhsO+UWwGBEBiv40ylRnkeSmHZEcp0z1Z83tpK/zGGCB
| QdAnME/nPQA=
|_-----END CERTIFICATE-----
|_ssl-date: 2023-11-26T17:18:48+00:00; +1s from scanner time.
|_ssl-known-key: ERROR: Script execution failed (use -d to debug)
5985/tcp  open  http          Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
|_http-server-header: Microsoft-HTTPAPI/2.0
|_http-title: Not Found
47001/tcp open  http          Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
|_http-title: Not Found
|_http-server-header: Microsoft-HTTPAPI/2.0
49664/tcp open  msrpc         Microsoft Windows RPC
49665/tcp open  msrpc         Microsoft Windows RPC
49666/tcp open  msrpc         Microsoft Windows RPC
49667/tcp open  msrpc         Microsoft Windows RPC
49668/tcp open  msrpc         Microsoft Windows RPC
49669/tcp open  msrpc         Microsoft Windows RPC
49670/tcp open  msrpc         Microsoft Windows RPC
49965/tcp open  ms-sql-s      Microsoft SQL Server 2019 15.00.2000.00; RTM
|_ms-sql-info: ERROR: Script execution failed (use -d to debug)
|_ms-sql-ntlm-info: ERROR: Script execution failed (use -d to debug)
|_ssl-date: 2023-11-26T17:18:48+00:00; +1s from scanner time.
| ssl-cert: OpenSSL required to parse certificate.
| -----BEGIN CERTIFICATE-----
| MIIDADCCAeigAwIBAgIQFZ3FFFdN3ZBBw1enPdrd/zANBgkqhkiG9w0BAQsFADA7
| MTkwNwYDVQQDHjAAUwBTAEwAXwBTAGUAbABmAF8AUwBpAGcAbgBlAGQAXwBGAGEA
| bABsAGIAYQBjAGswIBcNMjMwOTI3MDM0NjE2WhgPMjA1MzA5MjcwMzQ2MTZaMDsx
| OTA3BgNVBAMeMABTAFMATABfAFMAZQBsAGYAXwBTAGkAZwBuAGUAZABfAEYAYQBs
| AGwAYgBhAGMAazCCASIwDQYJKoZIhvcNAQEBBQADggEPADCCAQoCggEBANA05tdF
| oeXbccRvPN6YUnuoGnQI3xIc6tyHxiPZKN5ZCVOCp0TK3OXZxwLFUXJZemNivgmU
| MwP8/dEtFXtj3TygQWbbQagLY6KXpB99UHqLqgtDnC+kwXIpHFxpm6+CJRfKcQic
| XB46IwgL7RGzYZPJTJ+gt1rey/Un1M58bOb8pK4EBq4o/tGMbuP+aypMwfbNcmsV
| ovVIJoLNDpRdldm/AX+8gA/zKHHLPeRy3AQtL3kzoV6OpmH5EMshBrh2XDcjPKRO
| BfSPtDc0ZEoR+fDb8HmU1oZwSSQIXp7zs1a36y06VB6DithhQ3vaSfmoA1FqE73G
| BOcne1gcg5oKjH0CAwEAATANBgkqhkiG9w0BAQsFAAOCAQEAwQpKCKjHSdaTb+3D
| vkdZS5Tm6iNE+gtHbV9JEO7IEG4C69XV3zUE1ZJW6Cwo9p4KQoYXNCFjkq828qFC
| HKmKYhS9gGexsDT/kEGbBl5yMlj9W9o4ggNiYXNpQJYW0xoziRzuJU3heDL1UTSk
| nGshbHe6BVPvi58A8vRLBHZ7/S7D/lzPbrUMDfFglCW2Hpt9vs5D6lOPuvT/cD3b
| WeQW6AMn81P6IZkNz1CPAxyHIs5XEOAo58JWk6m1l1NBj5TYYfQk/EXnbwJ5LCgK
| 86/BD563AG+qor6s64atODXhMDtGpnfIrrAfTUdhurhf2wLmMu37WJbYH/G7st7/
| 0eW+KQ==
|_-----END CERTIFICATE-----
Warning: OSScan results may be unreliable because we could not find at least 1 open and 1 closed port
Device type: general purpose
Running (JUST GUESSING): Microsoft Windows 2022 (88%)
Aggressive OS guesses: Microsoft Windows Server 2022 (88%)
No exact OS matches for host (test conditions non-ideal).
Network Distance: 4 hops
Service Info: OS: Windows; CPE: cpe:/o:microsoft:windows

Host script results:
| smb2-security-mode: 
|   3:1:1: 
|_    Message signing enabled but not required
| smb2-time: 
|   date: 2023-11-26T17:18:41
|_  start_date: N/A

TRACEROUTE (using proto 1/icmp)
HOP RTT      ADDRESS
1   48.00 ms 192.168.45.1
2   47.97 ms 192.168.45.254
3   48.56 ms 192.168.251.1
4   48.66 ms 192.168.247.248

OS and Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 67.57 seconds
```