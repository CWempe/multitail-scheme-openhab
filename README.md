This projects adds a color schmeme for openhab logs to the multitail program.

# Installation

Add the content of `multitail-scheme-openhab.conf` to `/etc/multitail.conf`.  
Every file inside `var/log/openhab2/` will now get the openhab color scheme by default.

# Usage

Just open the log files like this:

```
sudo multitail /var/log/openhab2/events.log /var/log/openhab2/openhab.log
```

