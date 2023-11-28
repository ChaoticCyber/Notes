```
Nmap scan report for 10.7.0.7
Host is up (0.00035s latency).                                                                                                       
                                                                                                                                     
PORT      STATE  SERVICE              VERSION                                                                                        
22/tcp    open   ssh                  OpenSSH 7.1 (protocol 2.0)                                                                     
| ssh-hostkey:                                                                                                                                             
|   2048 c9c4c4278b31ea2cfb6a2f3891f72bad (RSA)                                                                                                            
|_  521 a5cf52673b7aacd2519249f522e5b5e4 (ECDSA)                                                                                                           
135/tcp   open   msrpc                Microsoft Windows RPC                                                                                                
139/tcp   open   netbios-ssn          Microsoft Windows netbios-ssn                                                                                        
445/tcp   open   microsoft-ds         Windows Server 2008 R2 Standard 7601 Service Pack 1 microsoft-ds                                                     
1234/tcp  open   hotline?                                                                                                                                  
1617/tcp  open   java-rmi             Java RMI                                                                                                             
| rmi-dumpregistry:                                                                                                                                        
|   jmxrmi                                                                                                                                                 
|     javax.management.remote.rmi.RMIServerImpl_Stub                                                                                                       
|     @10.7.0.7:49227                                                                                                                                      
|     extends                                                                                                                                              
|       java.rmi.server.RemoteStub                                                                                                                         
|       extends                                                                                                                                            
|_        java.rmi.server.RemoteObject                                                                                                                     
3000/tcp  open   http                 WEBrick httpd 1.3.1 (Ruby 2.3.3 (2016-11-21))                                                                        
|_http-title: Ruby on Rails: Welcome aboard                                                                                                                
|_http-server-header: WEBrick/1.3.1 (Ruby/2.3.3/2016-11-21)                                                                                                
| http-robots.txt: 1 disallowed entry 
|_/
3389/tcp  closed ms-wbt-server
3700/tcp  open   giop                 CORBA naming service
|_giop-info: ERROR: Script execution failed (use -d to debug)
4848/tcp  open   ssl/http             Oracle GlassFish 4.0 (Servlet 3.1; JSP 2.3; Java 1.8)
| ssl-cert: Subject: commonName=localhost/organizationName=Oracle Corporation/stateOrProvinceName=California/countryName=US
| Not valid before: 2013-05-15T05:33:38
|_Not valid after:  2023-05-13T05:33:38
|_ssl-date: 2023-11-28T14:48:57+00:00; +34m00s from scanner time.
|_http-server-header: GlassFish Server Open Source Edition  4.0 
|_http-title: Login
|_http-trane-info: Problem with XML parsing of /evox/about
5985/tcp  open   http                 Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
|_http-server-header: Microsoft-HTTPAPI/2.0
|_http-title: Not Found
7676/tcp  open   java-message-service Java Message Service 301
8009/tcp  open   ajp13                Apache Jserv (Protocol v1.3)
|_ajp-methods: Failed to get a valid response for the OPTION request
8019/tcp  open   qbdb?
8020/tcp  open   http                 Apache httpd
|_http-title: Site doesn't have a title (text/html;charset=UTF-8).
|_http-server-header: Apache
| http-methods: 
|_  Potentially risky methods: PUT DELETE
8022/tcp  open   http                 Apache Tomcat/Coyote JSP engine 1.1
|_http-title: Site doesn't have a title (text/html;charset=UTF-8).
|_http-server-header: Apache-Coyote/1.1
| http-methods: 
|_  Potentially risky methods: PUT DELETE
8027/tcp  open   papachi-p2p-srv?
8028/tcp  open   postgresql           PostgreSQL DB
8031/tcp  open   ssl/unknown
8032/tcp  open   desktop-central      ManageEngine Desktop Central DesktopCentralServer
8080/tcp  open   http                 Sun GlassFish Open Source Edition  4.0
|_http-server-header: GlassFish Server Open Source Edition  4.0 
|_http-open-proxy: Proxy might be redirecting requests
|_http-title: GlassFish Server - Server Running
| http-methods: 
|_  Potentially risky methods: PUT DELETE TRACE
8089/tcp  open   ssl/http             Splunkd httpd
|_http-server-header: Splunkd
|_http-title: splunkd
| ssl-cert: Subject: commonName=SplunkServerDefaultCert/organizationName=SplunkUser
| Not valid before: 2019-01-19T23:17:08
|_Not valid after:  2022-01-18T23:17:08
| http-robots.txt: 1 disallowed entry 
|_/
8181/tcp  open   ssl/intermapper?
| fingerprint-strings: 
|   GetRequest: 
|     HTTP/1.1 200 OK
|     Date: Tue, 28 Nov 2023 14:45:38 GMT
|     Content-Type: text/html
|     Connection: close
|     Content-Length: 4626
|     <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN">
|     <html lang="en">
|     <!--
|     ALTER OR REMOVE COPYRIGHT NOTICES OR THIS HEADER.
|     Copyright (c) 2010, 2013 Oracle and/or its affiliates. All rights reserved.
|     subject to License Terms
|     <head>
|     <style type="text/css">
|     body{margin-top:0}
|     body,td,p,div,span,a,ul,ul li, ol, ol li, ol li b, dl,h1,h2,h3,h4,h5,h6,li {font-family:geneva,helvetica,arial,"lucida sans",sans-serif; font-size:10pt}
|     {font-size:18pt}
|     {font-size:14pt}
|     {font-size:12pt}
|     code,kbd,tt,pre {font-family:monaco,courier,"courier new"; font-size:10pt;}
|     {padding-bottom: 8px}
|     p.copy, p.copy a {font-family:geneva,helvetica,arial,"lucida sans",sans-serif; font-size:8pt}
|     p.copy {text-align: center}
|     table.grey1,tr.grey1,td.g
|   HTTPOptions: 
|     HTTP/1.1 405 Method Not Allowed
|     Allow: GET
|     Date: Tue, 28 Nov 2023 14:45:38 GMT
|     Connection: close
|     Content-Length: 0
|   RTSPRequest: 
|     HTTP/1.1 505 HTTP Version Not Supported
|     Date: Tue, 28 Nov 2023 14:45:38 GMT
|     Connection: close
|_    Content-Length: 0
|_ssl-date: 2023-11-28T14:48:57+00:00; +34m00s from scanner time.
| ssl-cert: Subject: commonName=localhost/organizationName=Oracle Corporation/stateOrProvinceName=California/countryName=US
| Not valid before: 2013-05-15T05:33:38
|_Not valid after:  2023-05-13T05:33:38
8282/tcp  open   http                 Apache Tomcat/Coyote JSP engine 1.1
|_http-server-header: Apache-Coyote/1.1
|_http-favicon: Apache Tomcat
|_http-title: Apache Tomcat/8.0.33
8383/tcp  open   http                 Apache httpd
| http-methods: 
|_  Potentially risky methods: PUT DELETE
|_http-server-header: Apache
|_http-title: 400 Bad Request
8443/tcp  open   ssl/https-alt?
8444/tcp  open   desktop-central      ManageEngine Desktop Central DesktopCentralServer
8484/tcp  open   http                 Jetty winstone-2.8
|_http-server-header: Jetty(winstone-2.8)
| http-robots.txt: 1 disallowed entry 
|_/
|_http-title: Dashboard [Jenkins]
8585/tcp  open   http                 Apache httpd 2.2.21 ((Win64) PHP/5.3.10 DAV/2)
|_http-server-header: Apache/2.2.21 (Win64) PHP/5.3.10 DAV/2
|_http-title: WAMPSERVER Homepage
8686/tcp  open   java-rmi             Java RMI
| rmi-dumpregistry: 
|   dev01.supercorp.local/7676/jmxrmi
|     javax.management.remote.rmi.RMIServerImpl_Stub
|     @10.7.0.7:49761
|     extends
|       java.rmi.server.RemoteStub
|       extends
|         java.rmi.server.RemoteObject
|   jmxrmi
|     javax.management.remote.rmi.RMIServerImpl_Stub
|     @10.7.0.7:8686
|     extends
|       java.rmi.server.RemoteStub
|       extends
|_        java.rmi.server.RemoteObject
9200/tcp  open   wap-wsp?
| fingerprint-strings: 
|   FourOhFourRequest: 
|     HTTP/1.0 400 Bad Request
|     Content-Type: text/plain; charset=UTF-8
|     Content-Length: 80
|     handler found for uri [/nice%20ports%2C/Tri%6Eity.txt%2ebak] and method [GET]
|   GetRequest: 
|     HTTP/1.0 200 OK
|     Content-Type: application/json; charset=UTF-8
|     Content-Length: 311
|     "status" : 200,
|     "name" : "Kleinstocks",
|     "version" : {
|     "number" : "1.1.1",
|     "build_hash" : "f1585f096d3f3985e73456debdc1a0745f512bbc",
|     "build_timestamp" : "2014-04-16T14:27:12Z",
|     "build_snapshot" : false,
|     "lucene_version" : "4.7"
|     "tagline" : "You Know, for Search"
|   HTTPOptions: 
|     HTTP/1.0 200 OK
|     Content-Type: text/plain; charset=UTF-8
|     Content-Length: 0
|   RTSPRequest, SIPOptions: 
|     HTTP/1.1 200 OK
|     Content-Type: text/plain; charset=UTF-8
|_    Content-Length: 0
9300/tcp  open   vrace?
47001/tcp open   http                 Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
|_http-server-header: Microsoft-HTTPAPI/2.0
|_http-title: Not Found
49152/tcp open   msrpc                Microsoft Windows RPC
49153/tcp open   msrpc                Microsoft Windows RPC
49154/tcp open   msrpc                Microsoft Windows RPC
49173/tcp open   msrpc                Microsoft Windows RPC
49200/tcp open   unknown
49227/tcp open   java-rmi             Java RMI
49228/tcp open   tcpwrapped
49286/tcp open   ssh                  Apache Mina sshd 0.8.0 (protocol 2.0)
49287/tcp open   jenkins-listener     Jenkins TcpSlaveAgentListener
49334/tcp open   msrpc                Microsoft Windows RPC
49337/tcp open   msrpc                Microsoft Windows RPC
2 services unrecognized despite returning data. If you know the service/version, please submit the following fingerprints at https://nmap.org/cgi-bin/submit.cgi?new-service :
==============NEXT SERVICE FINGERPRINT (SUBMIT INDIVIDUALLY)==============
SF-Port8181-TCP:V=7.93%T=SSL%I=7%D=11/28%Time=6565F523%P=x86_64-pc-linux-g
SF:nu%r(GetRequest,128C,"HTTP/1\.1\x20200\x20OK\r\nDate:\x20Tue,\x2028\x20
SF:Nov\x202023\x2014:45:38\x20GMT\r\nContent-Type:\x20text/html\r\nConnect
SF:ion:\x20close\r\nContent-Length:\x204626\r\n\r\n<!DOCTYPE\x20HTML\x20PU
SF:BLIC\x20\"-//W3C//DTD\x20HTML\x204\.01\x20Transitional//EN\">\n<html\x2
SF:0lang=\"en\">\n<!--\nDO\x20NOT\x20ALTER\x20OR\x20REMOVE\x20COPYRIGHT\x2
SF:0NOTICES\x20OR\x20THIS\x20HEADER\.\n\nCopyright\x20\(c\)\x202010,\x2020
SF:13\x20Oracle\x20and/or\x20its\x20affiliates\.\x20All\x20rights\x20reser
SF:ved\.\n\nUse\x20is\x20subject\x20to\x20License\x20Terms\n-->\n<head>\n<
SF:style\x20type=\"text/css\">\n\tbody{margin-top:0}\n\tbody,td,p,div,span
SF:,a,ul,ul\x20li,\x20ol,\x20ol\x20li,\x20ol\x20li\x20b,\x20dl,h1,h2,h3,h4
SF:,h5,h6,li\x20{font-family:geneva,helvetica,arial,\"lucida\x20sans\",san
SF:s-serif;\x20font-size:10pt}\n\th1\x20{font-size:18pt}\n\th2\x20{font-si
SF:ze:14pt}\n\th3\x20{font-size:12pt}\n\tcode,kbd,tt,pre\x20{font-family:m
SF:onaco,courier,\"courier\x20new\";\x20font-size:10pt;}\n\tli\x20{padding
SF:-bottom:\x208px}\n\tp\.copy,\x20p\.copy\x20a\x20{font-family:geneva,hel
SF:vetica,arial,\"lucida\x20sans\",sans-serif;\x20font-size:8pt}\n\tp\.cop
SF:y\x20{text-align:\x20center}\n\ttable\.grey1,tr\.grey1,td\.g")%r(HTTPOp
SF:tions,7A,"HTTP/1\.1\x20405\x20Method\x20Not\x20Allowed\r\nAllow:\x20GET
SF:\r\nDate:\x20Tue,\x2028\x20Nov\x202023\x2014:45:38\x20GMT\r\nConnection
SF::\x20close\r\nContent-Length:\x200\r\n\r\n")%r(RTSPRequest,76,"HTTP/1\.
SF:1\x20505\x20HTTP\x20Version\x20Not\x20Supported\r\nDate:\x20Tue,\x2028\
SF:x20Nov\x202023\x2014:45:38\x20GMT\r\nConnection:\x20close\r\nContent-Le
SF:ngth:\x200\r\n\r\n");
==============NEXT SERVICE FINGERPRINT (SUBMIT INDIVIDUALLY)==============
SF-Port9200-TCP:V=7.93%I=7%D=11/28%Time=6565F518%P=x86_64-pc-linux-gnu%r(G
SF:etRequest,18E,"HTTP/1\.0\x20200\x20OK\r\nContent-Type:\x20application/j
SF:son;\x20charset=UTF-8\r\nContent-Length:\x20311\r\n\r\n{\r\n\x20\x20\"s
SF:tatus\"\x20:\x20200,\r\n\x20\x20\"name\"\x20:\x20\"Kleinstocks\",\r\n\x
SF:20\x20\"version\"\x20:\x20{\r\n\x20\x20\x20\x20\"number\"\x20:\x20\"1\.
SF:1\.1\",\r\n\x20\x20\x20\x20\"build_hash\"\x20:\x20\"f1585f096d3f3985e73
SF:456debdc1a0745f512bbc\",\r\n\x20\x20\x20\x20\"build_timestamp\"\x20:\x2
SF:0\"2014-04-16T14:27:12Z\",\r\n\x20\x20\x20\x20\"build_snapshot\"\x20:\x
SF:20false,\r\n\x20\x20\x20\x20\"lucene_version\"\x20:\x20\"4\.7\"\r\n\x20
SF:\x20},\r\n\x20\x20\"tagline\"\x20:\x20\"You\x20Know,\x20for\x20Search\"
SF:\r\n}\n")%r(HTTPOptions,4F,"HTTP/1\.0\x20200\x20OK\r\nContent-Type:\x20
SF:text/plain;\x20charset=UTF-8\r\nContent-Length:\x200\r\n\r\n")%r(RTSPRe
SF:quest,4F,"HTTP/1\.1\x20200\x20OK\r\nContent-Type:\x20text/plain;\x20cha
SF:rset=UTF-8\r\nContent-Length:\x200\r\n\r\n")%r(FourOhFourRequest,A9,"HT
SF:TP/1\.0\x20400\x20Bad\x20Request\r\nContent-Type:\x20text/plain;\x20cha
SF:rset=UTF-8\r\nContent-Length:\x2080\r\n\r\nNo\x20handler\x20found\x20fo
SF:r\x20uri\x20\[/nice%20ports%2C/Tri%6Eity\.txt%2ebak\]\x20and\x20method\
SF:x20\[GET\]")%r(SIPOptions,4F,"HTTP/1\.1\x20200\x20OK\r\nContent-Type:\x
SF:20text/plain;\x20charset=UTF-8\r\nContent-Length:\x200\r\n\r\n");
MAC Address: 00:0C:29:EE:E7:1C (VMware)
Device type: general purpose
Running: Microsoft Windows 7
OS CPE: cpe:/o:microsoft:windows_7::sp1
OS details: Microsoft Windows 7 SP1
Network Distance: 1 hop
Service Info: OSs: Windows, Windows Server 2008 R2 - 2012; Device: remote management; CPE: cpe:/o:microsoft:windows

Host script results:
| smb-os-discovery: 
|   OS: Windows Server 2008 R2 Standard 7601 Service Pack 1 (Windows Server 2008 R2 Standard 6.1)
|   OS CPE: cpe:/o:microsoft:windows_server_2008::sp1
|   Computer name: dev01
|   NetBIOS computer name: DEV01\x00
|   Domain name: supercorp.local
|   Forest name: supercorp.local
|   FQDN: dev01.supercorp.local
|_  System time: 2023-11-28T09:48:18-05:00
|_clock-skew: mean: 1h34m04s, deviation: 2h14m14s, median: 34m03s
| smb-security-mode: 
|   account_used: guest
|   authentication_level: user
|   challenge_response: supported
|_  message_signing: disabled (dangerous, but default)
| smb2-time: 
|   date: 2023-11-28T14:48:14
|_  start_date: 2023-11-28T14:12:04
| smb2-security-mode: 
|   210: 
|_    Message signing enabled but not required
|_nbstat: NetBIOS name: DEV01, NetBIOS user: <unknown>, NetBIOS MAC: 000c29eee71c (VMware)

TRACEROUTE
HOP RTT     ADDRESS
1   0.35 ms 10.7.0.7

OS and Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 233.94 seconds
```