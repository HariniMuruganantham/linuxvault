# User Management in Linux

Linux is a multi-user operating system. Each user has a unique user ID (UID).

---

## Important Files

| File | Purpose |
|------|--------|
| /etc/passwd | Stores user account information |
| /etc/shadow | Stores encrypted passwords |
| /etc/group  | Stores group information |

---

## Creating Users

Add a new user:

$ sudo useradd username

Create user with home directory:

$ sudo useradd -m username

Set password:

$ sudo passwd username

---

## Modifying Users

Change login name:

$ sudo usermod -l newname oldname

Change home directory:

$ sudo usermod -d /home/newdir username

Lock user account:

$ sudo usermod -L username

Unlock user account:

$ sudo usermod -U username

---

## Deleting Users

Delete user:

$ sudo userdel username

Delete user with home directory:

$ sudo userdel -r username

---

## Switching Users

Switch to another user:

$ su username

Check current user:

$ whoami
