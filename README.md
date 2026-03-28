# 4.Execution_of_NetworkCommands
## AIM :Use of Network commands in Real Time environment
## Software : Command Prompt And Network Protocol Analyzer
## Procedure: To do this EXPERIMENT- follows these steps:
<BR>
In this EXPERIMENT- students have to understand basic networking commands e.g cpdump, netstat, ifconfig, nslookup ,traceroute and also Capture ping and traceroute PDUs using a network protocol analyzer 
<BR>
All commands related to Network configuration which includes how to switch to privilege mode
<BR>
and normal mode and how to configure router interface and how to save this configuration to
<BR>
flash memory or permanent memory.
<BR>
This commands includes
<BR>
• Configuring the Router commands
<BR>
• General Commands to configure network
<BR>
• Privileged Mode commands of a router 
<BR>
• Router Processes & Statistics
<BR>
• IP Commands
<BR>
• Other IP Commands e.g. show ip route etc.
<BR>
program:

```
client.py:
import socket

s = socket.socket()
s.connect(('localhost', 8000))

while True:
    h = input("Enter the website you want to ping (or type 'exit' to quit): ")
    s.send(h.encode())
    if h == 'exit': break
    print(s.recv(4096).decode())

s.close()
```

## Output
<img width="1604" height="294" alt="image" src="https://github.com/user-attachments/assets/72055487-3b3d-4c5b-81d4-f9c48b882989" />

<img width="1598" height="186" alt="image" src="https://github.com/user-attachments/assets/4c67f409-8c97-45bc-87ba-8bc83a8aac73" />

## Result
Thus Execution of Network commands Performed 
