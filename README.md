# bluezberry-pi
Bluetooth Tools for the Pi

This is a collection of bluez related scripts modified to fit my usage.

* Copy `tools/*` to `/usr/local/bin`, copy the systemd service to `/etc/systemd/system`.
* Run `systemctl daemon-reload`, `systemctl enable simple-agent.service`, and then `systemctl start simple-agent.service`
