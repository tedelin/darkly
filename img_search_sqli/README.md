# [Injection](https://owasp.org/Top10/A03_2021-Injection/)

## Exploit

```sh
1 UNION SELECT url, comment FROM list_images --
```

## Solution

- Use ORM (Object Relational Mapping).
- Server-side input validation
- Sanitize user input (escape special characters)
