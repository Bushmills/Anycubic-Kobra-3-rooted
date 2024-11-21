
= Only usable with printer firmware prior to version 2.3.3.1

In this repo will I describe the steps necessary to:
 - gain root access to the Kobra 3 over network
 - copy files (expecially: rendered gcode files) over the network to Kobra 3

This serves to avoid having to use the (rather unreliable) "cloud" access to feed
the printer with data, while allowing use of a locally running slicer.

It also helps me to trace the changes done to the default printer configuration.

Steps are [here described and organised as wiki pages](https://github.com/Bushmills/Anycubic-Kobra-3-rooted/wiki/Top)

----

Current app version 1.4.6 from Play store (2024jul23) seems faulty - It terminates right after launch attempt on three different phones on which I tried it. Version 1.4.5, restored from backup, starts again. "Support" has been advised of the problem.

It seems that the app will, beginning with v1.4.6, not run on rooted phones any longer. This decision disqualifies Anycubic for my uses: Designing the firmware such that the device is hard to use without the app, while restricting the app to unrooted mobile devices is a combination of requirements which I find unacceptable.
Consequence: Anycubic, you just lost a customer. I'll go with less restrictive devices.

[Kingroon KLP1](https://github.com/Bushmills/Kingroon-KLP1-rooted/wiki) comes with nice and open firmware (full klipper running on vanilla Armbian installation). Also Creality, with their K1 and K1 max, finds it valuable to preinstall their devices with klipper.

Most recent addition to my printer park is a Sovol SV08 - again, rather open firmware:  apparently Armbian, with Klipper, ssh login, sudo for root, and stuff preinstalled not unlike the KLP1. Debian package management works out of the box.
