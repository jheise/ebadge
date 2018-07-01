EBADGE
---

Script to drive an Epaper screen on a raspberry pi zero and take input from a Pimoroni Buttonshim

The badge will display randomly choosen slogans from /var/badge/slogans.txt and will display properly formatted bitmaps from /var/badge/images, the badge then sleeps for a short interval.

Buttons have the following actions
Button A - Pause badge, solid red light when paused
Button B - Trigger random text
Button C - Trigger random image
Button D - Increase sleep interval by 5 seconds, for a maximum of 30
Button E - Decrease sleep interval by 5 seconds, for a minimum of 5
