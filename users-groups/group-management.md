# Group Management in Linux

Groups are used to manage permissions for multiple users.

Each group has a unique group ID (GID).

---

## Important File

| File | Purpose |
|------|--------|
| /etc/group | Stores group information |

---

## Creating Groups

Create a new group:

$ sudo groupadd developers

---

## Modifying Groups

Add user to group:

$ sudo usermod -aG developers username

Change group name:

$ sudo groupmod -n newgroup oldgroup

---

## Deleting Groups

Delete a group:

$ sudo groupdel developers

---

## Viewing Group Membership

View groups of a user:

$ groups username

Check group file:

$ cat /etc/group
