# Syncthing

## Installation

Run `sudo dnf install syncthing` and then run `syncthing`. A webpage should open. Decline anonymous usage reporting.

Download Syncthing on Android, and make sure to disable battery optimizations when prompted to. Delete the Camera folder that is added by default.

Add the Syncthing GUI to Firefox's Enahnced Tracking Protection exceptions and Cookies and Site Data exceptions.

To enable the program to run at login as a user sesion, open Terminal and run `systemctl --user enable --now syncthing.service`. The user session service will not be restarted automatically after the package is updated. The user will have to restart syncthing from the web interface, log out and back in, or run the following commands in Terminal:

```
systemctl --user daemon-reload
systemctl --user restart syncthing.service
```
