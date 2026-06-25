# 📘 Lecture 36 – Date, Time, and NTP (Linux)

---

## ❓ Review Questions & Answers

### 1. What command displays the current date and time?
```bash
date
2. Why is system time important?

System time is important because it is used for:

File timestamps
Logs
Security certificates (SSL/TLS)
Authentication systems
Scheduled tasks (cron jobs)
3. Which command changes only the date?
sudo date -s "2026-06-15"
4. Which command changes only the time?
sudo date -s "10:30:00"
5. Which command changes both date and time?
sudo date -s "2026-06-15 10:30:00"
6. Why must a System Administrator verify changes?

To ensure:

Correct system time is set
Logs and security systems remain accurate
Applications and services function properly
7. What is NTP?

NTP (Network Time Protocol) is a protocol used to automatically synchronize system time with accurate time servers over a network.

8. Why are timestamps important?

Timestamps are important for:

Tracking events in logs
Debugging system issues
File versioning and backups
Security auditing
9. What problems can incorrect time cause?

Incorrect time can cause:

SSL certificate errors
Authentication failures
Cron job misbehavior
Logging confusion
Data sync issues
10. How can you verify the current system time?
date

or

timedatectl
📒 ORIGINAL QUESTIONS (AS ASKED IN LECTURE 36)
What command displays the current date and time?
Why is system time important?
Which command changes only the date?
Which command changes only the time?
Which command changes both date and time?
Why must a System Administrator verify changes?
What is NTP?
Why are timestamps important?
What problems can incorrect time cause?
How can you verify the current system time?
🧪 Lab Summary

In this lecture, you learned how to:

Display system date and time using date
Change system date and time using date -s
Understand system time importance
Use timestamps in system operations
Understand NTP synchronization
Verify system time using date and timedatectl
🔧 Key Concepts
System time affects security, logs, and applications
NTP keeps system clocks synchronized automatically
Incorrect time can break authentication and HTTPS connections
System administrators must ensure correct time configuration
⏱️ Troubleshooting Flow
Check time:
date
Check sync status:
timedatectl
Enable NTP:
sudo timedatectl set-ntp true