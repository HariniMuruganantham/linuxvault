# Linux File Permissions – Basics

Linux controls access to files using permissions.

There are three permission types:

| Symbol | Meaning |
|--------|---------|
| r | read |
| w | write |
| x | execute |

There are three permission categories:

| Category | Meaning |
|----------|---------|
| u | user (owner) |
| g | group |
| o | others |

---

## Viewing Permissions

$ ls -l

Example output:

-rwxr-xr-- 1 user group 1024 file.txt

Breakdown:

- `-`  → file type  
- `rwx` → user permissions  
- `r-x` → group permissions  
- `r--` → others permissions

---

## Numeric Permission Values

| Permission | Value |
|-----------|-------|
| r | 4 |
| w | 2 |
| x | 1 |

Example:

rwx = 7  
rw- = 6  
r-x = 5  
r-- = 4  
--- = 0
