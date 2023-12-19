# internsctl - Custom Linux Command

## Overview

`internsctl` is a custom Linux command designed for various system operations. It provides functionalities to retrieve CPU and memory information, manage users, and obtain file details.

## Usage

### Manual Page
`internsctl --help`

### Version
`internsctl --version`
Executing the above command will display the version of the command.

### CPU Information 
`internsctl --cpu`
Executing the above command will retrieve CPU information.

### Memory Information 
`internsctl --memory`
Executing the above command will retrieve memory information

### Memory Information 
`internsctl --memory`

# User Management
### Create a New User
`internsctl user create <username>`
The above command creates a new user who can log in to the Linux system and access their home directory.

### List Users
`internsctl user list`

###List all regular users.
`internsctl user list --sudo-only`

# File Information 

### Get File Information
`internsctl file getinfo <file-name>`

### Expected Output Format
`File  : <LINUX_TASK>
Access : -rw-r--r--
Size(B): 5448
Owner  : <Abhishek_Kumar_Singh>
Modify : <13:01:23>`




