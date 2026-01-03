# Process Management in Linux

A process is a running instance of a program.

Each process has a unique Process ID (PID).

---

## Viewing Processes

List all running processes:

$ ps aux

Search process by name:

$ pgrep ssh

Get PID of a process:

$ pidof sshd

---

## Monitoring Processes

$ top  
$ htop

---

## Killing Processes

Kill process by PID:

$ kill 1234

Force kill:

$ kill -9 1234

Kill by process name:

$ killall firefox  
$ pkill chrome
