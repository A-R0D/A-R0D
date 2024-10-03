layout: default
title: Adrian Rodriguez - Cybersecurity 
---

# Adrian Rodriguez - Aspiring Cybersecurity Professional

Welcome to my GitHub Page! I am passionate about Cybersecurity and Information Assurance. Explore my projects, certifications, and resources below.

## About Me
I’m currently pursuing my Bachelor's in Cybersecurity and Information Assurance at Western Governors University, I am eager to learn and grow in this industry. 

<img src="./assets/AdrianCPIC.png" alt="Profile Picture" width="200"/>

---

## Projects

### Network Security Monitoring
A project where I used Wireshark to analyze network traffic for malicious activities.

[View Project](https://github.com/your-username/network-monitoring)

### Forensics Investigation
Leveraged FTK and Autopsy to conduct a thorough digital forensic investigation into a policy violation.

[View Project](https://github.com/your-username/forensics-investigation)

---

## Certifications
- **CompTIA A+** - January 2024
- **CompTIA Network+** - April 2024
- **CompTIA Security+** - July 2024

---

## Skills & Tools

| Skill           | Level        | Experience |
|-----------------|--------------|------------|
| Network Security | Advanced     | 3 years    |
| Digital Forensics| Intermediate | 2 years    |
| Wireshark        | Beginner     | 1 year     |

---

## Featured Code Snippet

python
# Python script for basic network scanning
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
