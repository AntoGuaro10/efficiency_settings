# efficiency_settings for raspberry pi4
Contains useful script and strings that help your raspberry pi efficiency

I'm actually using my raspberry pi4 as a pi-hole server, so beacuse i only want to filter the dns request from the hosts belonged to the LAN, i want the maximum efficiency for my little SoC (the raspberry itself).

I searched on internet and also in Github and i found this helpful scripts that worked fine to me.

My machine is connected only through ethernet cable to my modem, and the wlan0 interface is turned off using "sudo ifconfig wlan0 down".
I set a static IPv4 address and make sure that the eth0 interface was setting UP and that i can connect through SSH into my raspberry.
Than i started to turn off remotrly the wi-fi and bt modem, the HDMI interface and all the LEDs of my raspberry.

Hope this will be helpful for you as it was for me.
