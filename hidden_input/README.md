# [Broken Access Control](https://owasp.org/Top10/A01_2021-Broken_Access_Control/)

## Exploit

```html
<input type="hidden" name="mail" value="tedelin@student.42.fr" maxlength="30" />
```

## Solution

Do not hide input field in html this is not secure. And does not rely only on client side check.
