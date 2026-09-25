# Umbrella

**Type:** Challenge
**Focus:** Web Security, Docker, Enumeration, Privilege Escalation

## Tools Used

* Nmap
* cURL
* MySQL
* Docker
* Linux

## What I Did

* Scanned the target and identified open ports and services.
* Enumerated the web application and exposed Docker Registry.
* Investigated the Docker Registry and application image.
* Identified exposed database credentials within the application configuration.
* Accessed the database and investigated the available information.
* Investigated the web application and identified an unsafe use of `eval()`.
* Used the vulnerability to gain access to the Docker container.
* Investigated the container configuration and mounted directories.
* Exploited a container misconfiguration to escalate privileges on the host.

## Key Learnings

* How to enumerate exposed services and Docker Registries.
* How sensitive information can be exposed through application configurations.
* Basic Docker and container enumeration.
* How unsafe use of `eval()` can create a security vulnerability.
* Understanding the difference between gaining root access inside a container and gaining root access on the host.
* How container misconfigurations can lead to privilege escalation.

## Takeaway

This room helped me understand how web applications, Docker containers, databases, and host systems can be connected and how a misconfiguration in one area can lead to further compromise.

[Achievement](https://tryhackme.com/room/umbrella?utm_campaign=social_share&utm_medium=social&utm_content=share-completed-room&utm_source=copy&sharerId=6a4e29ff9527d8a079012a7a)
