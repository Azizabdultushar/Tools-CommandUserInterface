# Basic Windows CMD Commands

- Power consumption report from windows
- $ powercfg -energy
- extraction of report in html
- $ energy-report.html
- Power curve




## 1. Navigation Commands
- `cd [directory]`
  - Change the current directory to the specified directory.
  - Example: `cd C:\Users`

- `cd ..`
  - Move up one directory level.
  - Example: From `C:\Users\Admin`, `cd ..` takes you to `C:\Users`.

- `dir`
  - List all files and directories in the current directory.

- `tree`
  - Display the directory structure of the current folder in a tree format.

## 2. File Management Commands
- `copy [source] [destination]`
  - Copy files from one location to another.
  - Example: `copy file.txt D:\Backup`

- `move [source] [destination]`
  - Move files to a new location.
  - Example: `move file.txt D:\Backup`

- `del [filename]`
  - Delete a file.
  - Example: `del file.txt`

- `rmdir [directory] /s /q`
  - Remove a directory and all its contents.
  - `/s`: Remove all subdirectories and files.
  - `/q`: Suppress confirmation prompts.

- `ren [oldname] [newname]`
  - Rename a file or directory.
  - Example: `ren oldfile.txt newfile.txt`

## 3. System Information Commands
- `ipconfig`
  - Display IP configuration details.
  - Example: Shows your IP address, subnet mask, and gateway.

- `systeminfo`
  - Display detailed system information, including OS version, memory, and hardware.

- `tasklist`
  - Show a list of running processes.

- `taskkill /pid [PID] /f`
  - Kill a process by its Process ID (PID).
  - Example: `taskkill /pid 1234 /f`

## 4. Disk and Drive Management
- `chkdsk [drive:]`
  - Check a drive for errors.
  - Example: `chkdsk C:`

- `diskpart`
  - Launch Disk Partition Manager.

- `format [drive:]`
  - Format a drive.
  - Example: `format D:`

- `vol [drive:]`
  - Display the volume label and serial number.
  - Example: `vol C:`

## 5. Network Commands
- `ping [hostname or IP]`
  - Test network connectivity to a hostname or IP address.
  - Example: `ping google.com`

- `netstat`
  - Display active TCP connections and ports.

- `tracert [hostname or IP]`
  - Trace the route packets take to a hostname or IP address.
  - Example: `tracert google.com`

- `nslookup [domain]`
  - Get DNS information for a domain.
  - Example: `nslookup google.com`

## 6. Miscellaneous Commands
- `cls`
  - Clear the Command Prompt screen.

- `echo [text]`
  - Display a message or turn command echoing on/off.
  - Example: `echo Hello, World!`

- `exit`
  - Close the Command Prompt.

- `help`
  - List available commands and their usage.

- `shutdown /s /t [seconds]`
  - Shut down the computer after a delay.
  - Example: `shutdown /s /t 60`

- `shutdown /r /t [seconds]`
  - Restart the computer after a delay.
  - Example: `shutdown /r /t 60`

## 7. Advanced Commands
- `fc [file1] [file2]`
  - Compare two files and display their differences.
  - Example: `fc file1.txt file2.txt`

- `findstr [string] [filename]`
  - Search for a string in a file.
  - Example: `findstr "error" logfile.txt`

- `set`
  - View or set environment variables.

- `assoc`
  - Display or change file association for a file extension.

---
### Note:
- Some commands may require **Administrator Privileges**. Right-click on the Command Prompt icon and choose **Run as Administrator**.
