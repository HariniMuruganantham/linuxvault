# Introduction to the Linux Shell

The Linux shell is a command program where commands are typed.

It sends commands to the Linux OS and immediately displays the output in the same window.

The shell is powerful and flexible compared to graphical interfaces.

Every Linux administrator must understand the shell.

---

## Starting Point – Home Directory

When a user logs in, Linux places the session in the home directory.

Home directories are stored under `/home`.

Example:

$ pwd  
/home/username

Symbol for the home directory:

~

The initial prompt indicates that the current location is the home directory.

---

## Confirming Current Location

To check the current directory:

$ pwd  
Print Working Directory.

---

## echo Command

The `echo` command prints output to the screen.

Example:

$ echo Hello  
Hello

Options:

- `-n` → prints text without a trailing newline.

Example:

$ echo -n Hi
