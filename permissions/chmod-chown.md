# chmod and chown Commands

Linux allows changing permissions and ownership of files and directories.

---

## chmod – Change Mode

Change permissions using numeric values:

$ chmod 755 script.sh

Symbolic mode:

$ chmod u+x script.sh  
$ chmod g-w file.txt  
$ chmod o+r file.txt

---

## Recursive Permission Change

$ chmod -R 755 project/

---

## chown – Change Ownership

Change file owner:

$ sudo chown user file.txt

Change owner and group:

$ sudo chown user:group file.txt

---

## Recursive Ownership Change

$ sudo chown -R user:group project/
