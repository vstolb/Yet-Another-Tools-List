# Yet-Another-Tools-List

**By and for pentesters and security researchers who love collecting tools lists. Includes lists of other lists.** 


### Directory Traversal

Tool | Description
---- | ----
[DotDotPwn](https://github.com/wireghoul/dotdotpwn) 			| It's a very flexible intelligent fuzzer to discover traversal directory vulnerabilities in software such as HTTP/FTP/TFTP servers, Web platforms such as CMSs, ERPs, Blogs, etc.

### Password Brute Forcing and Dictionary Attacks

Tool | Description
---- | ----
[CeWL](https://tools.kali.org/password-attacks/cewl) 			| CeWL is a ruby app which spiders a given url to a specified depth, optionally following external links, and returns a list of words which can then be used for password crackers such as John the Ripper.
[THC Hydra](https://tools.kali.org/password-attacks/hydra)								| Hydra is a parallelized login cracker which supports numerous protocols to attack.
[Patator](https://tools.kali.org/password-attacks/patator)								| Patator is a multi-purpose password brute-forcer and fuzzer, with a modular design and a flexible usage. 
[Crawbar](https://github.com/galkan/crowbar)								| Crowbar (formally known as Levye) is a brute forcing tool that can be used during penetration tests. It was developed to brute force some protocols in a different manner according to other popular brute forcing tools. As an example, while most brute forcing tools use username and password for SSH brute force, Crowbar uses SSH key(s). This allows for any private keys that have been obtained during penetration tests, to be used to attack other SSH servers.
[ssh_login](https://www.offensive-security.com/metasploit-unleashed/scanner-ssh-auxiliary-modules/)								| Metasploit module. The ssh_login module is quite versatile in that it can not only test a set of credentials across a range of IP addresses, but it can also perform brute-force login attempts. 

### SSH

Tool | Description
---- | ----
[ssh2-enum-algos](https://nmap.org/nsedoc/scripts/ssh2-enum-algos.html) 			| NSE script. Reports the number of algorithms (for encryption, compression, etc.) that the target SSH2 server offers. If verbosity is set, the offered algorithms are each listed by type.
[ssh-hostkey](https://nmap.org/nsedoc/scripts/ssh-hostkey.html) 			| NSE script. Shows SSH hostkeys.
[sshv1](https://nmap.org/nsedoc/scripts/sshv1.html) 			| NSE script. Checks if an SSH server supports the obsolete and less secure SSH Protocol Version 1.
[Crawbar](https://github.com/galkan/crowbar)								| Crowbar (formally known as Levye) is a brute forcing tool that can be used during penetration tests. It was developed to brute force some protocols in a different manner according to other popular brute forcing tools. As an example, while most brute forcing tools use username and password for SSH brute force, Crowbar uses SSH key(s). This allows for any private keys that have been obtained during penetration tests, to be used to attack other SSH servers.
[ssh_login](https://www.offensive-security.com/metasploit-unleashed/scanner-ssh-auxiliary-modules/)								| Metasploit module. The ssh_login module is quite versatile in that it can not only test a set of credentials across a range of IP addresses, but it can also perform brute-force login attempts. 
[THC Hydra](https://tools.kali.org/password-attacks/hydra)								| Hydra is a parallelized login cracker which supports numerous protocols to attack.

### DLL Attacks

Tool | Description
---- | ----
[Rattler](https://github.com/sensepost/rattler) 			| Automated DLL enumerator.

### Web Content Brute Forcing

Tool | Description
---- | ----
[Burp Suite](https://tools.kali.org/web-applications/burpsuite) 			| Burp Suite is an integrated platform for performing security testing of web applications. Its various tools work seamlessly together to support the entire testing process, from initial mapping and analysis of an application’s attack surface, through to finding and exploiting security vulnerabilities.
[DirBuster](https://tools.kali.org/web-applications/DirBuster) 			| DirBuster is a multi threaded java application designed to brute force directories and files names on web/application servers.
[DIRB](https://tools.kali.org/web-applications/dirb) 			| DIRB is a Web Content Scanner. It looks for existing (and/or hidden) Web Objects. It basically works by launching a dictionary based attack against a web server and analyzing the response.
[Wfuzz](https://tools.kali.org/web-applications/wfuzz) 			| Wfuzz is a tool designed for bruteforcing Web Applications, it can be used for finding resources not linked (directories, servlets, scripts, etc), bruteforce GET and POST parameters for checking different kind of injections (SQL, XSS, LDAP,etc), bruteforce Forms parameters (User/Password), Fuzzing,etc.
[GoBuster](https://github.com/OJ/gobuster) 			| Directory/file & DNS busting tool written in Go


### Fuzzing, Brute Forcing, and Other For-Use-As-Part-Of-Pentest Lists

Tool | Description
---- | ----
[ssh-badkeys](https://github.com/rapid7/ssh-badkeys) 			| This is a collection of static SSH keys (host and authentication) that have made their way into software and hardware products. 
[SecLists](https://github.com/danielmiessler/SecLists) 			|  It is a collection of multiple types of lists used during security assessments. List types include usernames, passwords, URLs, sensitive data grep strings, fuzzing payloads, and many more.
[Reverse Shell Cheat Sheet](http://pentestmonkey.net/cheat-sheet/shells/reverse-shell-cheat-sheet) 			|  Various vays of setting up a reverse shell.

### Known Vulnerability and Exploits Lists

Tool | Description
---- | ----
[Exploit DB](https://www.exploit-db.com/) 			|  The Exploit Database – ultimate archive of Exploits, Shellcode, and Security Papers.
[Searchsploit](https://www.exploit-db.com/searchsploit/) 			|  The offline version of Exploit DB. Useful for not having to prove you're a human.
[CVE Details](http://www.cvedetails.com/) 			|  CVE Details
[Security Focus](http://www.securityfocus.com/) 			|  Includes information on vulnerabilities, exploits, etc.
[PacketStorm](https://packetstormsecurity.com/files/tags/exploit/) 			|  Exploits list on PacketStorm
[vFeed](https://github.com/toolswatch/vFeed) 			|  The Correlated Vulnerability And Threat Intelligence Database API

### Hardening

Tool | Description
---- | ----
[CIS Benchmarks](https://www.cisecurity.org/) 			|  CIS Benchmarks and CIS Controls are consensus-based guides curated by security practitioners focused on performance, not profit.

### Educational Lists

Tool | Description
---- | ----
[HTTP STatus Codes](https://en.wikipedia.org/wiki/List_of_HTTP_status_codes) 			|  HTTP Status Codes.


