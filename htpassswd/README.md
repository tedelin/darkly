# Broken Access Control and Cryptographic Failures

## Exploit

Listing directory with gobuster and most knowns directory list
We can found a file htpasswd.
Searching for htpasswd file we can found that file contain credentials hashed in md5. Using a tool like this [one](https://crackstation.net/) we can found the flag.

```sh
root:437394baff5aa33daa618be47b75cb49
```

## Solution

- Disable directory listing and disable access to sensitive file like this one.
- Avoid deprecated cryptographic functions and padding schemes, such as MD5, SHA1, PKCS number 1 v1.5 .
- Use stronger encryption.
