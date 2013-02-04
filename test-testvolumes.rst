Test Volume
===========

This test is written in shell and does NOT use selenium or access the Console UI.  It simply connects to the previously spawned image where a volume has been attached and sends a command to format the volume.  If the volume formats, it returns success, else it fails.
