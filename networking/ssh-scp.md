# SSH and SCP

SSH provides secure remote login to Linux servers.

---

## Connecting to Remote Server

$ ssh username@server_ip

---

## Generate SSH Key

$ ssh-keygen

---

## Copy Public Key to Server

$ ssh-copy-id username@server_ip

---

## Secure Copy – SCP

Copy file to remote system:

$ scp file.txt username@server_ip:/home/username/

Copy file from remote system:

$ scp username@server_ip:/home/username/file.txt .
