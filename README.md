# Standalone Browser (aka Kiosk)

These files can be used to setup a browser-only interface for a debian system.
It uses the X server + openbox and (currently) chromium.

## Building & Installing
After installing the dependencies (apt install bc), you can build the .deb package with:
$> ./standalone_brwoser.buildeb
$> sudo dpkg -i standalone_browser.deb

## Launching
Launch the command as root but with a valid, .Xauthority user; e.g.,
$> sudo -u <user> standalone_browser
