# [Injection](https://owasp.org/Top10/A03_2021-Injection/)

## Exploit

```sql
1 UNION SELECT commentaire, countersign FROM users --
```

## Solution

- Use ORM (Object Relational Mapping).
- Server-side input validation
- Sanitize user input (escape special characters)
