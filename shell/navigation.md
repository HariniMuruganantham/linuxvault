# Navigating the File System

Linux provides multiple commands to move between directories and explore the file system.

---

## Listing Directory Contents

`ls` – list directory contents

$ ls

Options:

- `ls -a`  → show hidden files  
- `ls -l`  → long detailed listing  
- `ls -r`  → sort by time (newest first)  
- `ls -tr` → sort by time (oldest first)

---

## Creating Directories

`mkdir dirname` – create a directory

$ mkdir testdir

Create parent directories automatically:

$ mkdir -p parent/child

---

## Changing Directories

`cd dirname` – move into a directory

$ cd testdir

Move one level up:

$ cd ..

Go back to home directory:

$ cd

Specify absolute path:

$ cd /home/username/Documents

---

## Absolute vs Relative Path

**Absolute Path**  
Full location from root directory.

Example:

$ cd /home/username/dir

**Relative Path**  
Path based on the current working directory.

Example:

$ cd dir

---

## Saving Directory Path with pushd / popd

`pushd` – change directory and save current location  
`popd` – return to last saved directory
