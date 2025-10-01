# Linux Command Repository

## Introduction
Welcome to the Linux Command Repository! This repository is a collection of Linux commands suitable for beginners and advanced users. Whether you are new to Linux or looking to expand your command-line knowledge, this resource is here to help you.

### What is Linux?
Linux is a popular open-source operating system known for its power, flexibility, and robust command-line interface. Learning how to use Linux commands is essential for efficient system administration, development, and automation tasks.

## Commands
Below is a list of commonly used Linux commands categorized by their functionality. Each command is accompanied by a brief description of its purpose.

## File and Directory Operations
- `ls`: List directory contents.
- `cd`: Change directory.
- `pwd`: Print working directory.
- `mkdir`: Create directories.
- `rmdir`: Remove empty directories.
- `rm`: Remove files and directories.
- `cp`: Copy files and directories.
- `mv`: Move/rename files and directories.
- `touch`: Create empty files or update timestamps.
- `ln`: Create links between files.
- `tree`: Display directory tree structure.
- `basename`: Extract filename from path.
- `dirname`: Extract directory path.
- `realpath`: Display absolute path.

## File Permissions and Ownership
- `chmod`: Change file permissions.
- `chown`: Change file ownership.
- `chgrp`: Change group ownership.
- `umask`: Set default permissions.
- `sudo`: Execute a command as another user.
- `su`: Switch to another user.
- `visudo`: Edit sudoers file.
- `getfacl`: Get file access control lists.
- `setfacl`: Set file access control lists.

## File Searching
- `find`: Search for files and directories.
- `locate`: Quickly find files by name.
- `which`: Display the path to an executable.
- `whereis`: Locate binary, source, and manual page files.
- `grep`: Search text using patterns.
- `rgrep`: Recursively search text in files.
- `ag`: The Silver Searcher (fast text search).
- `ack`: Text search tool designed for programmers.

## Disk Management
## Disk Management
- `fdisk`: Partition table manipulator.
- `gdisk`: GUID Partition Table (GPT) partitioning tool.
- `parted`: Partition manipulation program.
- `mkfs`: Create a file system.
- `mount`: Mount a file system.
- `umount`: Unmount a file system.
- `df`: Display disk space usage.
- `du`: Estimate file and directory space usage.
- `fsck`: File system consistency check.
- `badblocks`: Check for bad blocks on a disk.
- `blkid`: Display block device attributes.
- `lsblk`: List block devices.
- `swapon`: Enable swap space.
- `swapoff`: Disable swap space.
- `fdisk -l`: List all partitions.
- `tune2fs`: Adjust tunable filesystem parameters.

## Process Management
- `ps`: List running processes.
- `top`: Display and update sorted information about running processes.
- `htop`: Interactive process viewer (enhanced top).
- `pgrep`: Find processes by name or other attributes.
- `pkill`: Kill processes by name or other attributes.
- `kill`: Terminate processes by PID.
- `killall`: Kill processes by name.
- `jobs`: Display active jobs.
- `bg`: Put jobs in the background.
- `fg`: Bring jobs to the foreground.
- `nohup`: Run commands immune to hangups.
- `screen`: Terminal multiplexer.
- `tmux`: Terminal multiplexer.
- `at`: Execute commands at specified time.
- `crontab`: Schedule commands to run periodically.

## System Information
- `uname`: Display system information.
- `whoami`: Display current username.
- `who`: Show who is logged on.
- `w`: Show who is logged on and what they are doing.
- `id`: Display user and group information.
- `uptime`: Show system uptime and load.
- `free`: Display memory usage.
- `lsb_release`: Display Linux Standard Base information.
- `lscpu`: Display CPU information.
- `lshw`: List hardware information.
- `lspci`: List PCI devices.
- `lsusb`: List USB devices.
- `dmidecode`: Display system hardware information.
- `inxi`: Display comprehensive system information.
- `neofetch`: Display system information with ASCII art.

## System Monitoring
- `top` or `htop`: Display system and process information.
- `vmstat`: Virtual memory statistics.
- `iostat`: Input/output statistics.
- `iotop`: Monitor I/O usage by processes.
- `sar`: Collect and report system activity.
- `watch`: Execute a program periodically.
- `dstat`: Display system resource statistics.
- `glances`: Cross-platform system monitoring tool.
- `nmon`: Performance monitoring tool.
- `atop`: Advanced system and process monitor.

## Memory and Performance
- `free`: Display memory usage.
- `sync`: Synchronize cached writes to persistent storage.
- `lsof`: List open files and processes.
- `fuser`: Identify processes using files or sockets.
- `pmap`: Display memory map of processes.
- `smem`: Memory usage reporting tool.
- `valgrind`: Memory debugging and profiling tool.

## Environment Variables and Shell
- `env`: Display environment variables.
- `export`: Set environment variables.
- `set`: Display or set shell variables.
- `unset`: Remove variables or functions.
- `alias`: Create command aliases.
- `unalias`: Remove command aliases.
- `history`: Command history.
- `which`: Show command location.
- `type`: Display command type.
- `echo`: Display text.
- `printf`: Format and print data.
- `read`: Read input from user.
- `source` or `.`: Execute commands from file.

## Job Control and Signals
- `jobs`: List active jobs.
- `bg`: Move jobs to background.
- `fg`: Move jobs to foreground.
- `disown`: Remove jobs from job table.
- `kill`: Send signals to processes.
- `trap`: Handle signals in scripts.
- `sleep`: Delay execution.
- `timeout`: Run command with time limit.

## System Services (systemd)
- `systemctl`: Control systemd services.
- `service`: Control system services (SysV).
- `systemctl start/stop/restart`: Service control.
- `systemctl enable/disable`: Service autostart.
- `systemctl status`: Service status.
- `journalctl`: Query systemd journal.
- `systemctl list-units`: List systemd units.
- `systemctl daemon-reload`: Reload systemd configuration.

## Text Processing
- `cat`: Concatenate and display file content.
- `less` and `more`: Page through file content.
- `head`: Display first lines of files.
- `tail`: Display last lines of files.
- `grep`: Search text using patterns.
- `egrep`: Extended grep with regular expressions.
- `fgrep`: Fast grep for fixed strings.
- `sed`: Stream editor for text manipulation.
- `awk`: Text processing and pattern scanning.
- `sort`: Sort lines in text files.
- `uniq`: Remove duplicate lines.
- `cut`: Remove sections from lines.
- `tr`: Translate or delete characters.
- `wc`: Word, line, character, and byte count.
- `comm`: Compare sorted files line by line.
- `diff`: Compare files line by line.
- `patch`: Apply differences to files.
- `join`: Join lines of files on common fields.
- `paste`: Merge lines of files.
- `column`: Format input into columns.
- `fold`: Wrap text to specified width.
- `expand`: Convert tabs to spaces.
- `unexpand`: Convert spaces to tabs.

## File Transfer and Networking
- `scp`: Securely copy files between hosts.
- `rsync`: Synchronize files and directories.
- `ftp`: File Transfer Protocol client.
- `sftp`: Secure FTP client.
- `ncftp`: Improved FTP client.
- `curl`: Transfer data with URLs.
- `wget`: Download files from the internet.
- `aria2`: Multi-protocol download utility.
- `rclone`: Sync files to cloud storage.

## Network Configuration and Troubleshooting
- `ping`: Send ICMP echo requests.
- `ping6`: Send ICMPv6 echo requests.
- `traceroute`: Trace the route to a host.
- `tracepath`: Trace network path to destination.
- `mtr`: Network diagnostic tool (traceroute + ping).
- `netstat`: Display network statistics.
- `ss`: Display socket statistics (modern netstat).
- `dig`: DNS lookup utility.
- `nslookup`: Query DNS records.
- `host`: DNS lookup tool.
- `whois`: Query domain registration information.
- `ifconfig`: Configure network interfaces (legacy).
- `ip`: Show/manipulate routing, network devices.
- `route`: Display or modify the routing table.
- `arp`: Display/modify ARP table.
- `ethtool`: Display/change Ethernet device settings.
- `iwconfig`: Configure wireless network interface.
- `iwlist`: Scan for wireless networks.
- `nc` (netcat): Network utility for reading/writing network connections.
- `telnet`: Network protocol client.
- `ssh`: Secure Shell remote login.

## Firewall and Security
- `iptables`: Configure firewall rules (legacy).
- `ip6tables`: Configure IPv6 firewall rules.
- `ufw`: Uncomplicated Firewall management.
- `firewall-cmd`: Firewall management (firewalld).
- `fail2ban`: Intrusion prevention framework.
- `tcpdump`: Capture and analyze network packets.
- `wireshark`: Network protocol analyzer.
- `nmap`: Network discovery and security auditing.
- `openssl`: Cryptography toolkit.
- `gpg`: GNU Privacy Guard encryption.
- `ssh-keygen`: Generate SSH key pairs.
- `chmod`: Change file permissions.
- `chattr`: Change file attributes.
- `lsattr`: List file attributes.

## Text Editors
- `nano`: Simple, user-friendly text editor.
- `vim` or `vi`: Powerful modal text editor.
- `emacs`: Extensible, customizable text editor.
- `gedit`: GNOME graphical text editor.
- `kate`: KDE advanced text editor.
- `sublime-text`: Sublime Text editor.
- `code`: Visual Studio Code.
- `micro`: Modern terminal-based text editor.
- `joe`: Easy-to-use text editor.

## Archive Management
- `tar`: Create and extract tar archives.
- `gzip`: Compress files with gzip.
- `gunzip`: Decompress gzip files.
- `bzip2`: Compress files with bzip2.
- `bunzip2`: Decompress bzip2 files.
- `zip`: Create zip archives.
- `unzip`: Extract zip archives.
- `rar`: Create rar archives.
- `unrar`: Extract rar archives.
- `7z`: Create and extract 7z archives.
- `xz`: Compress files with LZMA algorithm.
- `unxz`: Decompress xz files.
- `zcat`: Display compressed file contents.
- `zgrep`: Search compressed files.
- `compress`: Compress files (legacy).
- `uncompress`: Decompress compressed files.

## User Management
- `useradd`: Add a new user.
- `userdel`: Delete a user.
- `usermod`: Modify user settings.
- `passwd`: Change user password.
- `chpasswd`: Change passwords in batch.
- `groupadd`: Add a new group.
- `groupdel`: Delete a group.
- `groupmod`: Modify group settings.
- `groups`: Display groups a user belongs to.
- `newgrp`: Change current group.
- `gpasswd`: Administer groups.
- `finger`: Display user information.
- `last`: Show last logins.
- `lastlog`: Show last login times.
- `ac`: Display user connection time.

## Package Management
### Debian/Ubuntu (APT)
- `apt`: Advanced package tool.
- `apt-get`: Package handling utility.
- `apt-cache`: Package cache manipulation.
- `dpkg`: Debian package manager.
- `dpkg-query`: Query installed packages.

### Red Hat/CentOS/Fedora
- `yum`: Package manager (older systems).
- `dnf`: Package manager (newer systems).
- `rpm`: RPM package manager.
- `rpm2cpio`: Convert RPM to cpio archive.

### Other Distributions
- `zypper`: OpenSUSE package manager.
- `pacman`: Arch Linux package manager.
- `emerge`: Gentoo package manager.
- `snap`: Snap package manager.
- `flatpak`: Application distribution framework.
- `appimage`: Portable application format.

## System Backup and Restore
- `tar`: Create and extract backups.
- `rsync`: Synchronize files and directories.
- `dd`: Copy and convert files at low level.
- `dump`: Backup filesystem (ext2/3/4).
- `restore`: Restore filesystem from dump.
- `cpio`: Copy files to/from archives.
- `rsnapshot`: Filesystem snapshot utility.
- `borgbackup`: Deduplicating backup program.
- `timeshift`: System restore utility.

## System Configuration and Time
- `hostname`: Display or set system hostname.
- `hostnamectl`: Control system hostname (systemd).
- `date`: Display or set system date and time.
- `timedatectl`: Control system time and date (systemd).
- `hwclock`: Hardware clock utility.
- `ntpdate`: Set system time via NTP.
- `chrony`: NTP client and server.
- `locale`: Display or set system locale.
- `localectl`: Control system locale (systemd).
- `tzselect`: Select timezone interactively.
- `shutdown`: Shutdown or restart system.
- `reboot`: Reboot system.
- `halt`: Halt the system.
- `poweroff`: Power off the system.
- `init`: Change system runlevel.

## System Logging
- `journalctl`: Query systemd journal.
- `syslog`: System log daemon.
- `rsyslog`: Reliable system log daemon.
- `logrotate`: Log rotation utility.
- `dmesg`: Display kernel messages.
- `logger`: Add entries to system log.
- `tail -f`: Follow log files in real-time.
- `multitail`: Monitor multiple log files.

## Hardware Information
- `lshw`: List hardware information.
- `lscpu`: Display CPU information.
- `lspci`: List PCI devices.
- `lsusb`: List USB devices.
- `lsblk`: List block devices.
- `lsmod`: List loaded kernel modules.
- `modinfo`: Display module information.
- `modprobe`: Load/unload kernel modules.
- `rmmod`: Remove kernel modules.
- `insmod`: Insert kernel modules.
- `dmidecode`: Display hardware information from BIOS.
- `hdparm`: Hard disk parameters.
- `smartctl`: Control SMART disk monitoring.
- `sensors`: Display hardware sensor information.
- `acpi`: Display ACPI information.

## Input/Output and Redirection
- `echo`: Display text.
- `printf`: Format and print data.
- `cat`: Display file contents.
- `tee`: Write output to file and stdout.
- `xargs`: Build command lines from input.
- `yes`: Output a string repeatedly.
- `seq`: Generate sequences of numbers.
- `shuf`: Generate random permutations.
- `nl`: Number lines.
- `pr`: Format files for printing.

## Shell Scripting and Programming
- `bash`: Bourne Again Shell.
- `sh`: POSIX shell.
- `zsh`: Z Shell.
- `fish`: Friendly Interactive Shell.
- `if`: Conditional statements.
- `for`: Loop constructs.
- `while`: Loop constructs.
- `case`: Conditional evaluation.
- `test` or `[`: Evaluate expressions.
- `expr`: Evaluate expressions.
- `bc`: Basic calculator.
- `dc`: Desk calculator.
- `factor`: Factor numbers.

## File System and Disk Utilities
- `fsck`: File system check.
- `e2fsck`: Ext2/3/4 file system check.
- `mkfs.ext4`: Create ext4 filesystem.
- `mkfs.xfs`: Create XFS filesystem.
- `mkfs.btrfs`: Create Btrfs filesystem.
- `tune2fs`: Adjust ext2/3/4 filesystem parameters.
- `resize2fs`: Resize ext2/3/4 filesystems.
- `xfs_growfs`: Grow XFS filesystem.
- `btrfs`: Btrfs filesystem utilities.
- `zfs`: ZFS filesystem utilities.

## Compression and Encoding
- `base64`: Base64 encode/decode.
- `uuencode`: UUencode files.
- `uudecode`: UUdecode files.
- `od`: Dump files in octal/hex.
- `hexdump`: Display file contents in hex.
- `xxd`: Make hex dump or reverse.
- `strings`: Extract printable strings.
- `file`: Determine file type.
- `mime-type`: Determine MIME type.

## Development Tools
- `gcc`: GNU C compiler.
- `g++`: GNU C++ compiler.
- `make`: Build automation tool.
- `cmake`: Cross-platform build system.
- `git`: Version control system.
- `svn`: Subversion version control.
- `diff`: Compare files.
- `patch`: Apply patches to files.
- `indent`: C code formatter.
- `ctags`: Generate tag files.
- `objdump`: Display object file information.
- `nm`: List symbols from object files.
- `strip`: Remove symbols from object files.
- `ldd`: Print shared library dependencies.
- `strace`: Trace system calls.
- `ltrace`: Trace library calls.
- `gdb`: GNU debugger.
- `valgrind`: Memory debugging tool.

## Virtual Machines and Containers
- `docker`: Container platform.
- `podman`: Daemonless container engine.
- `kubectl`: Kubernetes command-line tool.
- `vagrant`: Virtual machine management.
- `vboxmanage`: VirtualBox command-line interface.
- `qemu`: Machine emulator and virtualizer.
- `virsh`: Virtual machine management.
- `lxc`: Linux containers.

## Database Tools
- `mysql`: MySQL database client.
- `psql`: PostgreSQL database client.
- `sqlite3`: SQLite database client.
- `mongosh`: MongoDB shell.
- `redis-cli`: Redis command-line interface.

## Web and HTTP Tools
- `curl`: Transfer data with URLs.
- `wget`: Download files from web.
- `httpie`: User-friendly HTTP client.
- `lynx`: Text-based web browser.
- `w3m`: Text-based web browser.

## System Cleanup and Maintenance
- `apt autoremove`: Remove unnecessary packages (Debian/Ubuntu).
- `apt autoclean`: Clean package cache (Debian/Ubuntu).
- `yum clean`: Clean package cache (Red Hat/CentOS).
- `bleachbit`: System cleaner.
- `tmpwatch`: Remove old temporary files.
- `logrotate`: Rotate log files.
- `vacuum`: Database maintenance.

## Miscellaneous Utilities
- `cal`: Display calendar.
- `bc`: Basic calculator.
- `units`: Unit conversion.
- `fortune`: Display random quotes.
- `cowsay`: Generate ASCII art of animals.
- `figlet`: Generate ASCII art text.
- `banner`: Print large banner text.
- `toilet`: Generate colored ASCII art.
- `sl`: Steam locomotive animation.
- `cmatrix`: Matrix-style terminal screensaver.
- `screenfetch`: Display system information with ASCII logo.
- `hollywood`: Fill terminal with Hollywood-style effects.

Please note that this list is not exhaustive, and Linux commands have various options and arguments. It's essential to consult the command's [manual page](https://www.linux.org/forums/linux-beginner-tutorials.123) using `man <command>` for detailed information and usage.

## Getting Help
- `man`: Display manual pages for commands.
- `info`: Display info documents.
- `help`: Get help for built-in commands.
- `whatis`: Display one-line manual page descriptions.
- `apropos`: Search manual page names and descriptions.
- `which`: Locate a command.
- `type`: Display command type and location.
- `--help`: Most commands support this flag for quick help.

## Contribution
We welcome contributions! If you'd like to contribute to this project, please check out our [Contribution Guidelines](Contribution.md).

## Code of Conduct
Please review our [Code of Conduct](CodeOfConduct.md) before participating in this project.

## License
This project is licensed under the [License](LICENSE).

Happy Linux command-line learning!
