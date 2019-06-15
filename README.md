# ds1820tousb
Linux kernel modul for USB thermometer ds1820b

Firmware & Userspace Treiber:https://www.poempelfox.de/ds1820tousb/

This USB module is written with hwmon.  
After connecting the USB, a new directory is created in /sys/class/hwmon.  
The temperature of the two sensors can be read by 'cat temp1' and 'cat temp2'.  
The sensors can be rescan by 'echo 1 > rescan' and reset by 'echo 1 > reset'.  
