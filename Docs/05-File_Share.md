# File Services
## Description

Set up file sharing within the Active Directory which can be accessed on a client machine.

## Lab Environment
- Windows Server 2022
- Windows Pro 10

### Types of Permissions
**Shared** - Network level control that only applies to network level control. Controls read/write/full control permissions.

**NTFS** - File System level control that applies to files and folders on disk volumes. Applies to local and network users, allowing controlled access to shared files. 

### Network Method Process
**Network** - Configured GPOs to automatically map network drives for users (permanent access) 
- Create a Shared Folder
    A shared folder named SHARED was created on Windows server's local C: drive.

    **Folder Path:**
    C:\SHARED

## Implement File Server Resource Manager (FSRM)