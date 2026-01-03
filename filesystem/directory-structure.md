# Linux Directory Structure

---

## Purpose

Linux organizes all files and directories in a single hierarchical tree structure
starting from the root directory `/`.

---

## Root Directory `/`

The root directory is the top-level directory in Linux.  
All files and folders exist under this directory.

---

## Important System Directories

| Directory | Purpose |
|----------|--------|
| /bin | Essential user commands |
| /sbin | System administration commands |
| /lib | Shared system libraries |
| /boot | Boot loader and kernel files |
| /etc | Configuration files |
| /dev | Device files |
| /proc | Virtual files for process info |
| /sys | Kernel and hardware interface |
| /var | Logs and variable data |
| /tmp | Temporary files |
| /usr | User utilities and programs |
| /home | User home directories |
| /mnt | Temporary mount points |
| /media | External devices |
| /srv | Service related data |

---

## Boot Process Flow

Power ON → BIOS / UEFI → Boot Loader → Kernel → systemd → Login

---

## Summary

- Linux uses a single root directory  
- All system files are organized in fixed directories  
- Understanding directory structure is essential for system administration