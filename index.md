---
layout: default
title: Adrian Rodriguez - Aspiring Cybersecurity Professional
---

# Adrian Rodriguez - Aspiring Cybersecurity Professional

Welcome to my GitHub Page! I am passionate about Cybersecurity and Information Technology. Explore my projects, certifications, and resources below.

## About Me
I am currently pursuing my Bachelor's in Cybersecurity and Information Assurance at Western Governors University. In addition to my studies, I work as a Peer Coach, helping students prepare for and pass the CompTIA A+ exam. I'm passionate about growing and learning in the cybersecurity field and excited to continue building on my foundational skill set as I advance in this industry

<img src="./assets/AdrianCPIC.png" alt="Profile Picture" width="200"/>

---

## Projects

### Network Security Monitoring
Used Wireshark to analyze network traffic for malicious activities.

[View Project](https://github.com/your-username/network-monitoring)

### Random Workout Generator
A Python project that generates random workouts to help you mix up your exercise routine. I developed this as part of my final for my Introduction to Python course.

[View Project](https://github.com/A-r0d/random-workout-generator)

---

## Certifications

- **CompTIA A+** - January 2024
- **CompTIA Network+** - April 2024
- **CompTIA Security+** - July 2024
- **ITIL** - September 2024

---

## Skills & Tools

| Skill           | Level        | 
|-----------------|--------------|
| Linux/Mac/Windows | Advanced     | 
| Microsoft 365 Suite/Teams | Advanced  |
| Cisco Webex       | Advanced      | 

---

## Featured Code Snippet

```python
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
