# Dynamic Application Security Testing (DAST) Tool

An automated cybersecurity tool designed to dynamically audit web applications for security vulnerabilities by simulating active, real-time payload injection attacks.

## Key Components
- **Vulnerability Scanning Pipeline:** Engineered automated scanning modules (`project.py`) capable of actively discovering, identifying, and mapping critical high-priority web vulnerabilities, including Cross-Site Scripting (XSS), Cross-Site Request Forgery (CSRF), and SQL Injection.
- **Network & Server Management:** Architected robust server connection protocols, asynchronous request handling, and dynamic response analysis (`server_connection.py`) to safely evaluate web servers without causing downtime or impacting target availability.

**Technologies Used:** Python, Network Sockets, HTTP/HTTPS Protocols, Multi-threading, Security Payload Injection, Web Security Auditing.
