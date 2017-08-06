## How to reproduce?

1. Install [caddy](https://caddyserver.com/) server, then `cd` to directory with project files
and execute on console:

```
> caddy
```

2. In Chrome browser: `https://localhost`

3. Make sure Chrome warns you about non-valid SSL certificate, choose 'Proceed anyway'
and try to click on text field and enter some text. Text should appear but focus is
not set on input field, so you should not see text cursor.