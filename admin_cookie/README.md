# [Cryptographic Failures](https://owasp.org/Top10/A02_2021-Cryptographic_Failures/)

## Exploit

Using decrypt tools such as this [one](https://crackstation.net/) we can find weak md5 hash

## Solution

- Avoid deprecated cryptographic functions and padding schemes, such as MD5, SHA1, PKCS number 1 v1.5 .
- Ensure up-to-date and strong standard algorithms, protocols, and keys are in place; use proper key management.
- Always use authenticated encryption instead of just encryption.
