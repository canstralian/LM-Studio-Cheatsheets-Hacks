# Useful macOS Commands

## File Operations
- `ls`: List directory contents
- `cd [directory]`: Change the current directory
- `cp [source] [destination]`: Copy file or directory
- `mv [source] [destination]`: Move or rename file or directory
- `rm [file]`: Remove file
- `rm -r [directory]`: Remove directory and its contents
- `touch [file]`: Create an empty file
- `cat [file]`: Display file contents
- `less [file]`: View file contents one page at a time
- `head [file]`: Display the first 10 lines of a file
- `tail [file]`: Display the last 10 lines of a file

## Directory Operations
- `mkdir [directory]`: Create a new directory
- `rmdir [directory]`: Remove an empty directory
- `pwd`: Print the current working directory
- `find [directory] -name [name]`: Find files and directories

## System Information
- `uname -a`: Display system information
- `top`: Display running processes
- `ps`: Display current processes
- `df -h`: Display disk space usage
- `du -h [directory]`: Display directory space usage
- `free -m`: Display memory usage

## File Permissions
- `chmod [permissions] [file]`: Change file permissions
- `chown [user]:[group] [file]`: Change file owner and group
- `umask [mask]`: Set default file permissions

## Networking
- `ping [host]`: Send ICMP ECHO_REQUEST to network hosts
- `ifconfig`: Configure network interfaces
- `netstat -tuln`: Display network connections, routing tables, interface statistics
- `ssh [user]@[host]`: Connect to a remote host via SSH

## Package Management
- `brew update`: Update Homebrew
- `brew upgrade`: Upgrade installed formulae
- `brew install [package]`: Install a package
- `brew remove [package]`: Remove a package
