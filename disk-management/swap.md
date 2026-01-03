# Swap Memory Management

Swap is disk space used as virtual memory when RAM is full.

---

## Creating Swap File

Create empty file:

$ sudo fallocate -l 1G /swapfile

Set permissions:

$ sudo chmod 600 /swapfile

Make swap area:

$ sudo mkswap /swapfile

Enable swap:

$ sudo swapon /swapfile

---

## Disable Swap

$ sudo swapoff /swapfile

---

## Check Swap Usage

$ swapon --show  
$ free -h
