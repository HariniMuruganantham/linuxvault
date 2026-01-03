# Disk Partitioning in Linux

Disk partitioning divides a physical disk into logical sections.

---

## Viewing Disks

$ lsblk  
$ fdisk -l

---

## Creating Partitions using fdisk

$ sudo fdisk /dev/sda

Commands inside fdisk:

- `n` – create new partition  
- `p` – primary partition  
- `d` – delete partition  
- `w` – write changes  
- `q` – quit without saving  

---

## Formatting Partition

Create ext4 filesystem:

$ sudo mkfs.ext4 /dev/sda1
