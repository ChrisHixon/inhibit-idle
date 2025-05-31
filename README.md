inhibit-idle
============

```
Usage: inhibit-idle [OPTION]... METHOD CMD [ARG]...

Run a command with idle inhibited. Example: inhibit-idle -s sleep 60

INHIBIT METHODS:
  -s, --screensaver     ScreenSaver (dbus)
  -l, --logind          logind/systemd (dbus)
  -w, --wayland         Wayland (protocol)

OPTIONS:
  -h, --help            display help
```
