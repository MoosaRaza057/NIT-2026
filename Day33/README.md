# Review Questions & Answers

## 1. What is the purpose of /etc/profile?

`/etc/profile` is a global configuration file that runs for all users when a Login Shell starts.

## 2. What is the purpose of /etc/bashrc?

`/etc/bashrc` is a global Bash configuration file that runs for interactive Non-Login Shells.

## 3. What command is used to create a backup?

```bash
cp /etc/profile /etc/profile_bak
```

## 4. Why should backups be created before making changes?

Backups allow you to restore the original file if a mistake causes problems.

## 5. What does the diff command do?

`diff` compares two files and shows the differences between them.

Example:

```bash
diff file1 file2
```

## 6. What does the md5sum command do?

`md5sum` generates a unique hash value for a file to verify its integrity.

Example:

```bash
md5sum file.txt
```

## 7. What does it mean when two files have the same MD5 hash?

It means the files are most likely identical and have the same content.

## 8. Which verification method is stronger: diff or md5sum?

`md5sum` is generally stronger for quick integrity verification because it compares the entire file content using a hash.

## 9. Why is backup verification important?

To ensure the backup was created successfully and can be used for recovery if needed.

## 10. What is the Golden Rule of Linux Administration?

**Always create and verify a backup before modifying any configuration file.**