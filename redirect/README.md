# [Broken Access Control](https://owasp.org/Top10/A01_2021-Broken_Access_Control/)

## Exploit

```sh
http://10.0.2.5/?page=redirect&site=intra.42.fr
```

## Solution

Only allow the parameters that are actually used
