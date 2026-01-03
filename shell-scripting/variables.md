# Shell Scripting – Variables

Variables are used to store values in shell scripts.

---

## Defining Variables

name=Linux

Access variable:

$ echo $name

---

## Environment Variables

View all environment variables:

$ printenv

---

## Special Variables

| Variable | Meaning |
|----------|---------|
| $0 | Script name |
| $1 | First argument |
| $# | Number of arguments |
| $@ | All arguments |
| $? | Exit status of last command |
