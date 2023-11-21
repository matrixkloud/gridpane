We initially ran a Local Manual Backup

```
gp backup example.com -local-single-site
```
However, this did not stop the spinning.

So, we ran another, but this time, it was Manual Remote (Backblaze)
```
gp backup example.com -remote-single-site backblaze
```
