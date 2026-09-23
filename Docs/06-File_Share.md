# File and Sharing Services
## Description

Set up file sharing within the Active Directory which can be accessed on a client machine.

## Lab Environment
- Windows Server 2022
- Windows Pro 10

### Types of Permissions
**Shared** - Network level control that only applies to network level control. Controls read/write/full control permissions.

**NTFS** - File System level control that applies to files and folders on disk volumes. Applies to local and network users, allowing controlled access to shared files. 

### Network Sharing Method Process
**Network Sharing Method** - Configured GPOs to automatically map network drives for users (permanent access) 

- Create a Shared Folder

    A shared folder named SHARED was created on Windows server's local C: drive.

    **Folder Path:**
    `C:\SHARED`

- Configured Shared permission on SHARED folder.

    - add pic

- Configured Security (NTFS) on SHARED folder

    - add pic

- Access Shared Resources via. Network Sharing Method

    - Created a new GPO called **Mapped Drives** on the Windows server 
    - add pic "new drive properties"
    - Link the Mapped Drives GPO under Users in the USA domain folder.
    - add pic

- Verify GPO on Client Machine
    - Log into a user that was created on the Windows Server.
    - add a pic
    - To enforce policies immediately, enter command: 
    
        `gpupdate /force`

    - Proceed to reboot the system
    - After reboot, verify the SHARED drive is visible 

## Implement File Server Resource Manager (FSRM)
**Objective:** created Quota Template and File Screen Template to manage File Storage. The general purpose for this lab is to simulate being an Admin and setting limits to the capacity of shared folders for best practice. 

**FRSM** - A suite of tools provided by Microsoft to help manage data that is stored on file servers. 