# Linux Help System

Linux provides built-in documentation tools to understand commands directly from the terminal.

---

## man Command

`man` displays the manual pages of commands.

Example:

$ man ls

Navigate inside man page:

- `↑ / ↓` – scroll up and down  
- `q` – quit  
- `/word` – search for a word  

---

## --help Option

Many commands provide short help using `--help`.

Example:

$ ls --help

---

## whatis Command

`whatis` shows a one-line description of a command.

Example:

$ whatis ls  
ls (1) – list directory contents

---

## apropos Command

`apropos` searches commands using keywords.

Example:

$ apropos user

This is useful when the exact command name is unknown.

---

## info Command

`info` displays command documentation in hypertext format.

Example:

$ info ls

---

## help Command

`help` shows help for shell built-in commands.

Example:

$ help cd
