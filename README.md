This projects adds a color schmeme for openhab logs to the multitail program.

# Installation

Add the content of `multitail-scheme-openhab.conf` to `/etc/multitail.conf`.  
Every file inside `var/log/openhab2/` will now get the openhab color scheme by default.

# Usage

Just open the log files like this:

```
sudo multitail /var/log/openhab2/events.log /var/log/openhab2/openhab.log
```

# Example

## before

![screenshot_before]

## after

![screenshot_after]


# Usefull links

I used the log4jnew color scheme as inspiration.  
[https://github.com/flok99/multitail/blob/master/multitail.conf#L675](https://github.com/flok99/multitail/blob/master/multitail.conf#L675)


Here are usefull explainations about the multitail.conf:  
[https://www.pantz.org/software/multitail/multitailconfig.html](https://www.pantz.org/software/multitail/multitailconfig.html)




[screenshot_before]: screenshots/multitail-openhab_before.PNG
[screenshot_after]: screenshots/multitail-openhab_after.PNG