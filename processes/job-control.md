# Job Control in Linux

Job control allows management of foreground and background processes.

---

## Running Process in Background

$ firefox &

---

## Listing Background Jobs

$ jobs

---

## Moving Jobs Between Foreground and Background

Send running job to background:

Press: Ctrl + Z  
Then run:

$ bg

Bring job to foreground:

$ fg

---

## Process Priority

Set priority while running program:

$ nice -n 10 command

Change priority of running process:

$ renice -n 5 1234
