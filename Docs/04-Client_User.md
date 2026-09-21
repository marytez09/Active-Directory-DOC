# Client Configuration
## Objective
Installed Windows 10 Pro Operating System to act as a client machine through a virtual machine that connects to the Domain Controller. The clients are used to simulate users logging into an enterprise network on their local network. The client machines are also utilized to test the validity of policies that were implemented though the Domain Controller.

### Environment
- Oracle VirtualBox
- Windows 10 Pro 

### Installation
- Configured domain controllers to a static IP on Domain Controller
    - Changed DNS servers to loop back 127.0.0.1 as preferred DNS
- Configure Ethernet Settings on Client Machine, set up DNS server to communicate to Domain Controller. 
    - Add Domain Controller IPv4 address into Client Machine preferred DNS. 
    - Ping Domain Controller (e.g, ping 10.x.x.x) to verify Client Machine is connected to Domain Controller. 




