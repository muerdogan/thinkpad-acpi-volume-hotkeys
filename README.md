# thinkpad-acpi-volume-hotkeys
bash script to enable volume hotkeys for old ibm thinkpads on linux-xfce
---------------------------------
This bash script fixes the issue while sound buttons work but they don't activate the on display notifications showing the volume
- Create a file called /etc/rc.local, make it executable (and then reboot the laptop.
- ubuntu 18.04 uses systemd but for backward compatibility is has a feature that creates automatically a rc.local systemd service if the presence of an executable /etc/rc.local is detected. Add the bash code in /etc/rc.local
- in OpenSuse  /etc/init.d/boot.local   instead of   /etc/rc.local
- to make executable >>  "chmod u+x /etc/rc.local"  or "chmod u+x /etc/init.d/boot.local"

Tested on Debian 10, Ubuntu 18.04 and OpenSuse 14 Leap on XFCE
Tested machines : IBM ThinkPad X2x, X3x, X4x, X6x(s), T23, T4x, T60
