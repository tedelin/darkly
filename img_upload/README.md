# [Security Misconfiguration](https://owasp.org/Top10/A05_2021-Security_Misconfiguration/)

## Exploit

We can edit the form request to change the type of the file header field and upload malicious php file :  
Content-Type: image/jpeg

## Solution

- Reject files based on MIME type and file extension (.php, .phtml, etc.).
- Use a strict allowlist (e.g., only image/jpeg, image/png).
- Do not trust Content-Type from user input.
