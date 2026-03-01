
I received this server from a friend of mine, thanks Luke!

In order to set this up properly I need a few things:
1. Keyboard
2. Mouse
3. VGA Cable
4. Monitor that accepts VGA Cable
5. Ethernet cable

After about two weeks, I was able to get all of these things.

When I powered up the machine, I was greeted by warning that said:

"warning: detected mode change from ATA mode to AHCI mode on the embedded SATA Controller. Data loss will occur"

I was not planning on keeping any of the data, as none of it was important. So I entered Y in order to continue.
Once I was through there were some messages that appeared on a screen. Here are some images of this:

![""](./Images/IMG_2973.jpg)
![""](./Images/IMG_2974.jpg)

The next step was to enter the system setup and change the controller to RAID configuration mode. However, I was unable to enter the BIOS and encountered a boot loop after each attempt. While I could successfully access iDRAC6, BIOS access was not possible.

These symptoms strongly suggest a dead CMOS battery, which prevents BIOS settings from being retained. As a result, the CMOS battery will need to be replaced.
