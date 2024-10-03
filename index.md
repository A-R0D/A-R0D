---
layout: default
title: Adrian Rodriguez - Cybersecurity
---

<style>
    body {
        background-color: #1e1e1e; /* Dark background */
        color: #f0f0f0; /* Light text color */
        font-family: 'Courier New', Courier, monospace; /* Monospace font for hacker aesthetic */
    }
    h1, h2, h3 {
        color: #00ff00; /* Green color for headers */
    }
    .container {
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 20px;
    }
    .profile {
        text-align: center;
        margin-bottom: 20px;
    }
    .code-snippet {
        background-color: #272822; /* Darker section background */
        padding: 15px;
        border-radius: 5px;
        box-shadow: 0 0 10px rgba(0, 255, 0, 0.5); /* Green glow effect */
        width: 80%;
        margin: 20px 0;
    }
    pre {
        background-color: #1e1e1e; /* Code background */
        border-radius: 5px;
        padding: 10px;
        overflow: auto; /* Enables scrolling for long code */
    }
    img {
        width: 200px; /* Adjust image size */
        border-radius: 5px;
        box-shadow: 0 0 10px rgba(0, 255, 0, 0.5); /* Green glow effect */
    }
    a {
        color: #00ff00; /* Green color for links */
    }
</style>

<div class="container">
    <div class="profile">
        <h1>Adrian Rodriguez - Aspiring Cybersecurity Professional</h1>
        <p>Welcome to my GitHub Page! I am passionate about Cybersecurity and Information Assurance. Explore my projects, certifications, and resources below.</p>
        <img src="./assets/AdrianCPIC.png" alt="Profile Picture" />
    </div>

    <h2>About Me</h2>
    <p>I’m currently pursuing my Bachelor's in Cybersecurity and Information Assurance at Western Governors University, eager to learn and grow in this industry.</p>

    <h2>Projects</h2>
    <div>
        <h3>Network Security Monitoring</h3>
        <p>A project where I used Wireshark to analyze network traffic for malicious activities.</p>
        <a href="https://github.com/your-username/network-monitoring">View Project</a>

        <h3>Forensics Investigation</h3>
        <p>Leveraged FTK and Autopsy to conduct a thorough digital forensic investigation into a policy violation.</p>
        <a href="https://github.com/your-username/forensics-investigation">View Project</a>
    </div>

    <h2>Certifications</h2>
    <ul>
        <li><strong>CompTIA A+</strong> - January 2024</li>
        <li><strong>CompTIA Network+</strong> - April 2024</li>
        <li><strong>CompTIA Security+</strong> - July 2024</li>
    </ul>

    <h2>Skills & Tools</h2>
    <table>
        <tr>
            <th>Skill</th>
            <th>Level</th>
            <th>Experience</th>
        </tr>
        <tr>
            <td>Network Security</td>
            <td>Advanced</td>
            <td>3 years</td>
        </tr>
        <tr>
            <td>Digital Forensics</td>
            <td>Intermediate</td>
            <td>2 years</td>
        </tr>
        <tr>
            <td>Wireshark</td>
            <td>Beginner</td>
            <td>1 year</td>
        </tr>
    </table>

    <h2>Featured Code Snippet</h2>
    <div class="code-snippet">
        <pre>
<code>
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
</code>
        </pre>
    </div>
</div>



```
The final element.
```
