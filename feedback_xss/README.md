# [Injection XSS](https://owasp.org/www-community/attacks/xss/)

## Exploit

```html
<img+onload ="alert('1')" />a
```

## Solution

Sanitize user input escape special character and does not allow html tags.
