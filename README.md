
# Screensaver Inhibitor

A PHP script to list the current screensaver inhibitors.

The script queries the D-Bus system for processes that are currently running and preventing your screensaver from kicking in.

* Why do I want that?

    When I go to bed, I like to lock my screen, only in the morning at times it's on. That's becomes a process (often Firefox) has an inhibitor in effect. The idea of the script is to find out what those processes are and close that tab or tool for the night.
    
## About Firefox

Note that for Firefox you can just switch to another tab which doesn't require inhibition and it will drop out of the list. If you have multiple Firefox windows opened, then you may need to go to each one to fix them all. Other browsers may have the same feature. I didn't try. Such functionality is going to be on a per process. It's how these tools handle D-Bus and not how D-Bus works.
