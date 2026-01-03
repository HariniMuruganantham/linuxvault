# Important Linux Commands – Master Cheatsheet

---

## System Information

| Command | Purpose |
|--------|--------|
| uname -a | Show all system information |
| uname -r | Kernel version |
| lscpu | CPU architecture |
| lsblk | Disk & partitions |
| free -h | Memory usage |
| df -h | Disk space |
| uptime | System running time |

---

## User Information

| Command | Purpose |
|--------|--------|
| who | Logged in users |
| w | Active users |
| whoami | Current user |
| last | Login history |

---

## File & Directory

| Command | Purpose |
|--------|--------|
| ls -la | List all files |
| cd /path | Change directory |
| pwd | Show current directory |
| mkdir -p dir | Create nested directory |
| rm -rf dir | Delete directory |
| cp -r src dst | Copy directory |
| mv old new | Rename / move |

---

## File Viewing

| Command | Purpose |
|--------|--------|
| cat file | View file |
| less file | Scroll file |
| head file | First lines |
| tail -f file | Live log view |

---

## Searching Files

| Command | Purpose |
|--------|--------|
| find / -name file | Find file |
| locate file | Quick search |
| grep -r text /path | Search text |

---

## Permissions

| Command | Purpose |
|--------|--------|
| chmod 755 file | Change permission |
| chown user:grp file | Change ownership |

---

## Process Management

| Command | Purpose |
|--------|--------|
| ps aux | Show all processes |
| top | Resource usage |
| kill -9 PID | Kill process |
| htop | Advanced monitor |

---

## Networking

| Command | Purpose |
|--------|--------|
| ip addr | IP address |
| ping host | Test network |
| traceroute host | Trace route |
| netstat -tuln | Open ports |
| ss -tuln | Modern netstat |

---

## Package Management

| Command | Purpose |
|--------|--------|
| apt update | Update repo |
| apt install pkg | Install pkg |
| yum install pkg | RHEL install |

---

## Systemd

| Command | Purpose |
|--------|--------|
| systemctl status ssh | Service status |
| systemctl start ssh | Start service |
| systemctl enable ssh | Enable at boot |
| journalctl -u ssh | View logs |

---

## Archive & Compression

| Command | Purpose |
|--------|--------|
| tar -czf file.tar.gz dir | Create archive |
| tar -xzf file.tar.gz | Extract |
| gzip file | Compress |
| unzip file.zip | Extract zip |

---

## Summary

This file provides the most important commands required for daily Linux administration.
