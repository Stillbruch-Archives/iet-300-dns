# iet-300-dns
## Helpers
To flush DNS cache on systems using systemd-resolv:
```sh 
sudo systemd-resolve --flush-caches
```
## Known Issues
* Reverse zones are probably not entirely correct.
