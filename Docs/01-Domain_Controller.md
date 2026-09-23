# Domain Controller Configuration
## Objective

Set up a Windows Server VM to serve as the Domain Controller for the Active Directory lab environment. The Domain Controller will be responsible for centralized services such as the creation of users, groups, and policies.

### Environment
- Oracle VirtualBox
- Windows Server 2022 

### Installation Process 
- Installed Windows Server 2022 on Oracle VirtualBox
    - Configured User and Password for Admin.

- Installed Active Directory through Server Manager
    - ### Server Rolls
        - Active Directory Domain Services
        - DHCP Server
        - DNS Server
        - File and Storage Services
        - Group Policy Management
        - pic

- Promoted Server to a Domain Controller
    - pic
    - Important step: This Active Directory lab is made from scratch, therefore a Domain Controller must be set.

- Deployment Configuration
    - Add a "new forest"
    - Root Domain Name: KikiCorp.local
    - NetBIOS domain name: KIKICORP

- Rebooted system - logged into newly created domain with configured Admin password/user.






