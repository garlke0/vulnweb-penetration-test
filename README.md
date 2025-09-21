# Vulnerability Testing Project

## Description
Web security project testing Reflected XSS, SQL Injection, and hidden directories on testphp.vulnweb.com.

## Tools
- Kali Linux
- SQLMap
- Feroxbuster
- Nikto

## Steps
1. Recon using Feroxbuster
2. Test XSS on guestbook.php
3. Test SQL Injection on login.php

## Results
- XSS executed successfully
- SQL Injection allowed login without password
- Hidden links discovered including database name

## Recommendations
- Sanitize input, encode output
- Use prepared statements
- Secure hidden directories
