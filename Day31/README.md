# Linux Shell & Login Process - Short Notes

## 1. What is PID 1?
PID 1 is the first process started by the Linux kernel. It is usually `systemd` and is the parent of all other processes.

## 2. What is the role of systemd?
`systemd` manages system startup, services, processes, logging, and system shutdown.

## 3. What is the difference between PID and PPID?
- **PID**: Process ID of a process.
- **PPID**: Parent Process ID that created the process.

## 4. What is a Login Shell?
A shell started after a successful login (console, SSH, `su - user`).

## 5. What is a Non-Login Shell?
A shell started from an existing session (opening a terminal, `bash`, `su user`).

## 6. What files are executed during login?
- `/etc/profile`
- `~/.bash_profile`
- `~/.bash_login`
- `~/.profile`

## 7. What is the purpose of .bashrc?
Stores user-specific shell settings, aliases, functions, and environment variables for interactive shells.

## 8. What is the purpose of .bash_profile?
Executed for login shells. Used to set environment variables and start user-specific settings.

## 9. What is the purpose of .bash_logout?
Runs commands when the user logs out.

## 10. What is PATH?
An environment variable containing directories where Linux searches for commands.

## 11. Why does Linux search PATH from left to right?
Linux searches directories in the order they appear in PATH and executes the first matching command found.

## 12. What command displays your shell PID?
```bash
echo $$
```

## 13. What command displays the current shell?
```bash
echo $SHELL
```

## 14. What command reloads .bashrc?
```bash
source ~/.bashrc
```

## 15. What command displays the process tree?
```bash
pstree
```

# Lab Summary

### Learned Topics
- Linux login process
- Why systemd is PID 1
- How sshd launches bash
- Difference between PID and PPID
- Login vs Non-Login Shell
- Global and user initialization files
- PATH and command lookup
- Creating custom commands
- Using .bash_logout
- Building a user environment

### Importance
These concepts are fundamental for:
- RHCSA
- RHCE
- Linux Administration
- DevOps
- System Engineering
- Infrastructure Operations