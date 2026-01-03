# Input / Output Redirections and Pipes

Linux allows redirection of input and output streams between commands and files.

There are three standard streams:

| Stream | Number | Description |
|-------|--------|-------------|
| STDIN | 0      | Input       |
| STDOUT| 1      | Output      |
| STDERR| 2      | Error       |

---

## Output Redirection

Overwrite file:

$ ls > files.txt

Append to file:

$ ls >> files.txt

---

## Input Redirection

Take input from a file:

$ sort < names.txt

---

## Error Redirection

Redirect only errors:

$ command 2> error.txt

Redirect output and errors:

$ command > all.txt 2>&1

---

## Pipes

Pipe sends output of one command as input to another.

Syntax:

$ command1 | command2

Example:

$ ls | grep ".txt"

---

## Combining Pipes and Redirection

Example:

$ ps aux | grep root > root-process.txt
