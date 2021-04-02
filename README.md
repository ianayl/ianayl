`/etc/systemd/system/boomer.service`:
```ini
[Unit]
# comedy gold
Description=BOOMER

[Service]
Type=simple
ExecStart=/usr/bin/sleep 0

[Install]
WantedBy=default.target
WantedBy=shutdown.target
WantedBy=poweroff.target
```
