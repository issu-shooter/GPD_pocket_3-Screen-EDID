Okay, here's what I've got.

I once again re-installed Manjaro on my P3, and again have to deal with the device's rotated portrait screen.
At first I followed the instructions on ArchWiki, edited the GRUB_CMDLINE_DEFAULT to pass kernel parameter,
however, the only the terminal got rotated, but the system haven't. I thought it could be my misconfiguration,
but soon I was told **GRUB boot commands will only work on the first instance installed on the disk**, so I refrained to use the OS with Plasma(Wayland)'s internal rotation funtion.

While I configured the system with fbcon and video=DSI-1 blah blah, I pluged an external monitor into my device, and I chose to mirror the screen.
BOOM, my P3's display ended up displaying a weird downscaled 1920x1080 screen in the middle part of a portrait 1200x1920 monitor.
