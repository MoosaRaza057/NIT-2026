# Linux Administration Questions & Answers

## 1. What command shows the kernel version?

```bash
uname -r
```

## 2. What command displays operating system information?

```bash
cat /etc/os-release
```

## 3. What is PID 1?

PID 1 is the first process started by the Linux kernel, usually `systemd`.

## 4. Why is systemd important?

`systemd` manages system startup, services, processes, and system shutdown.

## 5. What command displays your current shell?

```bash
echo $SHELL
```

## 6. What command displays your shell PID?

```bash
echo $$
```

## 7. What is the purpose of the /etc directory?

The `/etc` directory stores system-wide configuration files.

## 8. What is the difference between an Absolute Path and a Relative Path?

- **Absolute Path:** Starts from the root directory (`/`).
  Example:
  ```bash
  /etc/profile
  ```

- **Relative Path:** Starts from the current directory.
  Example:
  ```bash
  ./script.sh
  ```

## 9. What does the ping command test?

`ping` tests network connectivity and reachability between devices.

## 10. How do you stop a running process?

Press:

```bash
Ctrl + C
```

## 11. What are the two major Global Initialization Files?

```text
/etc/profile
/etc/bashrc
```

(Or `/etc/bash.bashrc` on Ubuntu/Debian.)

## 12. Why should configuration files be backed up before modification?

To allow recovery if a mistake causes problems or breaks the system.

## 13. What is the difference between rm and rmdir?

- `rm` removes files (and directories with `-r`).
- `rmdir` removes only empty directories.

Examples:

```bash
rm file.txt
```

```bash
rmdir empty_directory
```