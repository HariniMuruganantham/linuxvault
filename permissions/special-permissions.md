# Special Permissions in Linux

Linux provides special permission bits for advanced access control.

---

## SUID (Set User ID)

When SUID is set on a file, the file executes with the owner’s privileges.

Symbol: `s`  
Numeric value: 4

Set SUID:

$ chmod u+s file.sh

---

## SGID (Set Group ID)

When SGID is set on a directory, new files inherit the group of the directory.

Symbol: `s`  
Numeric value: 2

Set SGID:

$ chmod g+s project/

---

## Sticky Bit

Sticky bit prevents users from deleting files of others in a shared directory.

Symbol: `t`  
Numeric value: 1

Set sticky bit:

$ chmod +t /shared
