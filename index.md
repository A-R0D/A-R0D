---
layout: default
title: Adrian Rodriguez - Cybersecurity Specialist
---

# Adrian Rodriguez - Cybersecurity Specialist

Welcome to my GitHub Page! I am passionate about Cybersecurity and Information Assurance. Explore my projects, certifications, and resources below.

---

## About Me
I’m currently pursuing my Bachelor's in Cybersecurity and Information Assurance at Western Governors University, where I focus on network security and digital forensics. I'm passionate about helping organizations safeguard their information and improve their security posture.

![Profile Picture](./assets/profile-picture.jpg) <!-- Replace with your actual image file path -->

---

## Featured Projects

### Network Security Monitoring
In this project, I used Wireshark to monitor and analyze network traffic to detect potential threats and malicious activities.

[View Project](https://github.com/your-username/network-monitoring) <!-- Replace with actual URL -->

### Forensics Investigation
I used FTK and Autopsy to investigate and collect digital evidence for a company policy violation case. This project showcases my ability to gather and preserve digital evidence.

[View Project](https://github.com/your-username/forensics-investigation) <!-- Replace with actual URL -->

---

## Certifications

- **CompTIA A+**
- **CompTIA Network+**
- **CompTIA Security+**

---

## Skills & Tools

| Skill           | Level        | Experience |
|-----------------|--------------|------------|
| Network Security | Advanced     | 3 years    |
| Digital Forensics| Intermediate | 2 years    |
| Wireshark        | Beginner     | 1 year     |
| FTK              | Intermediate | 1 year     |
| Autopsy          | Intermediate | 1 year     |

---

## Sample Code

Here’s a sample of a Python script I wrote for basic network scanning:

```python
import socket

def scan(host):
    for port in range(1, 1024):
        sock = socket.socket(socket.AF_INET, socket.SOCK_STREAM)
        result = sock.connect_ex((host, port))
        if result == 0:
            print(f"Port {port}: Open")
        sock.close()

scan('192.168.1.1')

```
The final element.
```
