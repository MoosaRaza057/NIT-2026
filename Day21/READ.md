# Day 21 Lab - Linux Commands and Paths

## 1. How to Check Date and Time
Command:
```bash
date
```

This command displays the current system date and time.

---

## 2. How to Check System Uptime
Command:
```bash
uptime
```

This command shows:
- Current time
- How long the system has been running
- Number of logged-in users
- System load average

---

## 3. Difference Between Absolute and Relative Path

### Absolute Path
- Starts from the root directory `/`
- Complete path to a file or directory

Example:
```bash
/var/opt/images
```

### Relative Path
- Does not start with `/`
- Path depends on the current working directory

Example:
```bash
opt/images
```

---

## 4. How to Create Directory Using Absolute and Relative Path

### Using Absolute Path
```bash
mkdir /var/opt/images
```

### Using Relative Path
```bash
cd /var
mkdir opt/images
```

---

## 5. How to Create a Single File and Multiple Files

### Create a Single File
```bash
touch file1
```

### Create Multiple Files at the Same Time
```bash
touch file{1..10}
```

This command creates:
```bash
file1 file2 file3 ... file10
```