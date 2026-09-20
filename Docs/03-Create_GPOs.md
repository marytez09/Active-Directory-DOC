# Creating and Setting Up Group Policy Objects (GPOs)
## What is a GPO?

A GPO is a Windows feature that provides centralized management and configuration of user, computer, and settings. GPOs are useful when configuring Active Directories in defining security parameters and features. 

### List of GPOs 
- Password Policy
- Drive Mapping
- Mapped Drives
- Restrict Access to Control Panel
- Disable USB Storage
- Account Lockout Policy
- Desktop Wallpaper Policy


### GPO #1 Password Policy
Used to enforce strong passwords and enhance security, this policy changes the length, complexity and age of a password which is applied when a new user is created. 

### GPO #2 Drive Mapping
Maps network drives for users when they log in, simplifies file paths to access centralized data.

### GPO #3 Mapped Drives
Links a local drive letter (e.g. S:) to a shared folder on another computer/server. It's the drive a client sees on their computer after mapping is created.

### GPO #4 Restrict Access to Control Panel
Restricts Control Panel/Settings on client users.

### GPO #5 Disable USB Storage
Prevents users from using USB storage devices.

### GPO #6 Account Lockout Policy
Configures account lockout settings to prevent brute force attacks.

### GPO #7 Desktop Wallpaper Policy
Sets a default desktop wallpaper for all users. 

# Implementing and Testing GPOs
## Description
Configuring group policies and applying them to their respective 