# Operating System
---

## view running processes
---
- ps aux
- top(htop)

## check server uptime
---
- uptime
- top

## start/stop services
---
- (deprecated) service start/stop service_name
- systemctl start/stop service_name

## display the shell’s environment variables
---
- env
- printenv

## `#!/bin/bash` at the top of a script - purpose
---
It say to shell, what interpreter to use when run this script

## What does "&" after a command - purpose
---
It run command in background

## piping commands
---
piping with '|' transfer stdout of one command to another, for example,
```
ps aux | grep httpd
```
first command show all running processes, then, transfer stdout to stdin of second command, whose find only strings where 'httpd'.

## What distributions have you used on servers and Why
---
- Ubuntu - very fresh kernels and packages
- CentOS/RHEL - Enterprise and stability

## favorite editor
---

## RAID
---

## What is RAID0, RAID1, RAID5, RAID10
---

## Diﬀerence between RAID 0, 1 and 5
---

## What’s the advantage of one RAID over another
---

## General file system hierarchy of a Linux system.
---

## Describe what each of the following command line utilities do
---
### tee
---

### awk
---

### tr
---

### cut
---

### curl
---

### tail
---

### sed
---

## Command line demo
---
### Search for "my konfu is the best" in all *.py files
---

### Replace the occurrence of "my konfu is the best" with "I'm a linux jedi master" in all *.txt files
---

### Find all files which have been accessed within the last 30 days
---
  
## What is the difference between virtual memory and swap ?
---

## What is the difference between hardlinks and symlinks?
---

## What is an inode and what fields are stored in an inode?
---

## zombie processes
---

## What is the difference between processes and threads?
---

## exec vs fork
---

## What is "nohup" used for?
---

## What is an atomic operation?
---

## I've added my public ssh key into authorized_keys but I'm still getting a password prompt, what can be wrong?
---

## How do you catch a SIGHUP ? What about SIGSEGV ? What about SIGKILL ?
---

## What is the Linux Kernel OOM and how does it work ?
---

## chroot jail
---

## Describe the Linux boot process with as much detail as possible, starting from when the system is powered on and ending when you get a prompt.
---

## What's LD_PRELOAD and when is it used?
---

## You ran a binary and nothing happened. How would you debug this?
---
I run binary with strace, for example: strace binary_name

## When can a socket receive E_AGAIN ?
---

## What is a dynamically/statically linked file?
---

## A careless sysadmin executes the following command: chmod 444 /bin/chmod - what do you do to fix this?
---

## I've lost my root password, what can I do?
---

## You have accidentally deleted a running script, how could you restore it ?
---

## Alternative to init.d in Linux
---
