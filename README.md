# Cybersecurity Hands-On Portfolio

## Summary
Completed browser-based labs:
- SQL Injection
- Cross-Site Scripting (XSS)
- Authentication Bypass
- Command Injection
- File Inclusion

## PortSwigger Academy
- SQLi: Edited URL `?category=Gifts'+OR+1=1--` → listed all products
- XSS: `<script>alert('XSS Test')</script>` → popup executed

## Google Gruyere
- Snippet XSS: `<script>alert('Google XSS')</script>` → popup
- File upload: Uploaded `test.txt` with script → observed behavior

## OWASP WebGoat
- Login bypass: `admin' OR '1'='1'--` → logged in without password

## DVWA Online
- Command injection: `127.0.0.1; ls` → listed files
- File inclusion: `../../etc/passwd` → read system file
