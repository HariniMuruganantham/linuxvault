# Sudo and SSH

This file covers privilege escalation using sudo and remote login using SSH.

---

## sudo Command

`sudo` allows permitted users to execute commands as root.

Configuration file:

/etc/sudoers

Edit safely using:

$ sudo visudo

---

## Common sudo Commands

Run command as root:

$ sudo apt update

Switch to root shell:

$ sudo -i

---

## SSH – Secure Shell

SSH is used to connect securely to a remote Linux server.

Basic syntax:

$ ssh username@server_ip

---

## SSH Key Based Login

Generate SSH key:

$ ssh-keygen

Copy public key to server:

$ ssh-copy-id username@server_ip

---

## SCP – Secure Copy

Copy file to server:

$ scp file.txt username@server_ip:/home/username/

Copy file from server:

$ scp username@server_ip:/home/username/file.txt .
