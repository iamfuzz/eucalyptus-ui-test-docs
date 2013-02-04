Reboot Instance
===============

This test reboots the previously spawned instance and verifies that it is pingable after 20 seconds.  Currently the UI does not inform us when a reboot is occurring - it just stays in  the "Running" state.

TODO
====

Should probably do more testing to ensure the machine actually went down. (either ping test before/after, or perhaps connect to the instance and check uptime)
