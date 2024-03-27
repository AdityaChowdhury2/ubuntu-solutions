## How to Set a small password for ubuntu

Use following command in Terminal:

```
sudo passwd <user>
```

Replace <user> with the username whose password you wish to change.

This works because passwd suppresses all checks for length or entropy when you use it as the root user.
