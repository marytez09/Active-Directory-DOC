# Client Configuration
## Description
Configured a Windows client virtual machine that connects to the domain controller. This client is used to simulate users logging into an enterprise network on their local network. 

### Environment
- Oracle VirtualBox
- Windows 10 Pro ISO

### Installation
- Configured domain controllers to a static IP on **Domain Controller**
    - Changed DNS servers to loop back 127.0.0.1 as preferred DNS
- Configure Ethernet Settings on **Client OS**, set up DNS server to communicate to **Domain Controller**. 
    - Add **Domain Controller** IPv4 address into **Client OS** preferred DNS. 
    - Ping domain controller (e.g, ping 10.x.x.x) to verify client is connected to controller. 




