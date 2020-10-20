I'm not on systemd rn, and I'm too lazy to make a vm, but can someone pls try this and get back to me with what shows on boot? Thanks a lot lol

make`/etc/systemd/system/boomer.service`with the following:
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
