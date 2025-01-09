# Useful Windows Commands

## File Operations
- `dir`: List directory contents
- `cd [directory]`: Change the current directory
- `copy [source] [destination]`: Copy file or directory
- `move [source] [destination]`: Move or rename file or directory
- `del [file]`: Remove file
- `rmdir /s [directory]`: Remove directory and its contents
- `type [file]`: Display file contents
- `more [file]`: View file contents one page at a time

## Directory Operations
- `mkdir [directory]`: Create a new directory
- `rmdir [directory]`: Remove an empty directory
- `chdir`: Print the current working directory

## System Information
- `systeminfo`: Display system information
- `tasklist`: Display running processes
- `taskkill /IM [process_name] /F`: Kill a specific process
- `ipconfig`: Display IP configuration
- `netstat -an`: Display network connections, routing tables, interface statistics

## File Permissions
- `icacls [file] /grant [user]:[permissions]`: Change file permissions
- `icacls [file] /setowner [user]`: Change file owner

## Networking
- `ping [host]`: Send ICMP ECHO_REQUEST to network hosts
- `tracert [host]`: Trace route to network host
- `netsh`: Configure network interfaces
- `ssh [user]@[host]`: Connect to a remote host via SSH (requires OpenSSH installed)

## Package Management
- `choco upgrade all`: Upgrade all installed Chocolatey packages
- `choco install [package]`: Install a Chocolatey package
- `choco uninstall [package]`: Uninstall a Chocolatey package
