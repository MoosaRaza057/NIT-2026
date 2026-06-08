# Inode Questions and Answers

## 1. What is an inode?
An inode is a data structure in Linux that stores information about a file or directory.

---

## 2. What information is stored in an inode?
An inode stores:
- File size
- Owner ID
- Permissions
- Timestamps
- File type
- Disk block locations

---

## 3. Does an inode store the filename?
No, the filename is stored separately in the directory entry.

---

## 4. What command displays disk space usage?
```bash
df -h
```

---

## 5. What command displays inode usage?
```bash
df -i
```

---

## 6. Can a filesystem have free disk space but no free inodes?
Yes, it can happen when too many small files consume all inodes.

---

## 7. What happens when all inodes are consumed?
No new files can be created on the filesystem.

---

## 8. Why does Linux display "No space left on device" when no inodes remain?
Because the system cannot allocate a new inode for creating files.

---

## 9. Why do administrators monitor both disk usage and inode usage?
To ensure the filesystem has both free storage space and available inodes.

---

## 10. What command can be used to check inode utilization on a filesystem?
```bash
df -i
```