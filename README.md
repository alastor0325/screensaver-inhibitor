
# Screensaver Inhibitor

A PHP script to list the current screensaver inhibitors on Linux.

The script queries the D-Bus system for processes that are currently running and preventing your screensaver from kicking in.

* Why do I want that?

    When I go to bed, I like to lock my screen, only in the morning at times it's on. That's becomes a process (often Firefox) has an inhibitor in effect. The idea of the script is to find out what those processes are and close that tab or tool for the night.

* Why do you want that?

    You may have the same problem as I, or maybe you want the computer to be locked at all times when you're not at the computer. The lock won't happen if you have an inhibitor in place.

    Another reason would be that you expect the computer to go to sleep/hibernation after a while and the inhibitors will again prevent that from happening and you'll use electricity the whole time when it should be hibernating.

* Why did we invent such things?

    Whenever someone watches a video, they usually don't move their mouse or type on the keyboard and the movie may be 2 or 3 hours long. For that long the computer should not go to sleep.

* How to run

    1. Run `$ ./inhibitor`
    2. If there are active inhibitors, the script would show the requesters and the reason.

