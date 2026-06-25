## 📘 Review Questions (Short Answers)

**1. What does ping stand for?**  
Ping does not stand for anything official. It is named after sonar “ping”.

**2. Which protocol does ping use?**  
ICMP (Internet Control Message Protocol)

**3. What is ICMP?**  
A network layer protocol used for sending error messages and diagnostics.

**4. Why do network administrators use ping?**  
To test network connectivity and check if a host is reachable.

**5. What does `ping google.com` test?**  
DNS resolution + internet connectivity to the resolved IP.

**6. What does `ping 8.8.8.8` test?**  
Basic internet connectivity without DNS.

**7. What does the `-c` option do?**  
Sets the number of packets to send.

**8. What does the `-i` option do?**  
Sets the time interval between packets.

**9. What does the `-q` option do?**  
Quiet mode — shows only summary output.

**10. What does Ctrl + C do?**  
Stops a running command.

**11. What is the loopback address for IPv4?**  
127.0.0.1

**12. What is the loopback address for IPv6?**  
::1

**13. What does a successful loopback test indicate?**  
The local TCP/IP stack is working correctly.

---

## 🧪 Lab Summary

In this lab you learned how to:

- Use the `ping` command  
- Test network connectivity  
- Test internet access  
- Test DNS resolution  
- Send a specific number of packets (`-c`)  
- Adjust packet intervals (`-i`)  
- Show summary statistics (`-q`)  
- Test loopback interfaces (`127.0.0.1`, `localhost`)  
- View help options  
- Stop running processes using `Ctrl + C`

---

## 🔧 Important Troubleshooting Order

1. `ping 127.0.0.1`  
2. `ping localhost`  
3. `ping your own IP address`  
4. `ping your default gateway`  
5. `ping 8.8.8.8`  
6. `ping google.com`  

👉 This order helps identify exactly where the network problem is occurring.