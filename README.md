# TWRP for samsung galaxy tab A 8' 2019 (SM-T295) gto lte

$ heimdall flash --RECOVERY recovery_a.img --no-reboot
$ heimdall flash --RECOVERY recovery_b.img --no-reboot

*if the second flash of recovery_b.img got :
Initialising protocol...
ERROR: Protocol initialisation failed! ( just unplug the usb and plug it back ) then flash the second recovery_b.img
for the last file is vbmeta do the same before flashing (unplug usb & plug it back) not sure why maybe my usb port is broken..

$ heimdall flash --VBMETA vbmeta.img

*this time with no ( --no-reboot ) flag. standby to hold the vol up button after the flash done and when the phone is rebooting. done..TWRP install.
