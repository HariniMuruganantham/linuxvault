# File and Directory Operations

Linux provides several commands to create, copy, move, and delete files and directories.

---

## Creating Files

Create an empty file:

$ touch file1.txt

---

## Copying Files

`cp` – copy files or directories.

Copy file:

$ cp file1.txt file2.txt

Copy directory:

$ cp -r dir1 dir2

---

## Moving / Renaming Files

`mv` – move or rename files.

Rename file:

$ mv old.txt new.txt

Move file to another directory:

$ mv file1.txt /home/username/Documents/

---

## Deleting Files and Directories

Remove file:

$ rm file1.txt

Remove directory:

$ rm -r testdir

Force delete:

$ rm -rf testdir

---

## Viewing File Content

View entire file:

$ cat file1.txt

View page by page:

$ more file1.txt  
$ less file1.txt

View first lines:

$ head file1.txt

View last lines:

$ tail file1.txt
