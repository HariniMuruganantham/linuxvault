# Searching Files and Directories

Linux provides multiple commands to search for files and content efficiently.

---

## locate Command

`locate` searches files using a prebuilt database.

Example:

$ locate passwd

Update locate database:

$ sudo updatedb

Note: `locate` is fast but may not show recently created files unless the database is updated.

---

## find Command

`find` searches files in real time.

Basic syntax:

$ find path option expression

Examples:

Find file by name:

$ find / -name file.txt

Find directories only:

$ find /home -type d

Find files modified in last 1 day:

$ find /var/log -mtime -1

Find and delete files:

$ find /tmp -name "*.log" -delete

---

## grep Command

`grep` searches for text inside files.

Example:

$ grep "root" /etc/passwd

Search recursively:

$ grep -r "error" /var/log

Ignore case:

$ grep -i linux file.txt

---

## Combining find and grep

Search text inside specific file types:

$ find /var/log -name "*.log" -exec grep "error" {} \;
