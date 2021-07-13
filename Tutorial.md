# Schimb acest text!

**Sometimes you might get an issue with the VPN when the user has a Killer E220 NIC. This guide describes how to replace the driver for the NIC and make the VPN work properly again.**

Here is a small guide on how to get Windows to see your Killer E2200 NIC as a Qualcomm Atheros AR8161 PCI-E Gigabit Ethernet Controller.... [!badge Tutorial time!]

*the Killer E2200 NIC is actually more or less a Qualcomm Atheros AR8161 chip.*

 1. Download the Driver for the Qualcomm Atheros AR8161 using the following button [!file](../downloads/Killer.atheros.zip)

2. Transfer it to agent's PC and unpack it somewhere.

3. Go into Device Manager. (Right click on Computer-->Properties then on the left side under "Control Panel Home" you see "Device Manager"

4. When "Device Manager" opens locale and expand "Network Adapters", you do that by clicking on the arrow head or double click on it.

![This is a test caption](../images/capture1.png)

5. When "Network Adapters" is expanded you show see your Killer E2200 NIC
=== Network Adapters
Killer E2200 NIC
===

6. Right click on the "Killer E2200 NIC" and choose "Update Driver Software..."

7. These Next steps are important so follow them carefully....

Choose "Browse my computer for driver software"

8. Now choose "Let me pick from a list of device drivers on my computer

[!badge variant="Danger" text="Important"]***:if you just do it as you normally with with "Search for a driver software in this location:" you will get that "Windows was unable to install the driver" (And no this isn't because i already have the driver installed it's because Windows see's the card as a Killer E2200 NIC):*** 

9. Click on the "Have Disk..." button:

- and then hit the "Browse" button, and go into where you have unpacked the driver, then find the folder called "Common_Dri"

Choose the folder that matches your OS like for Windows 7 32bit u take "Win7_32", for Windows 7 64bit u take "Win7_64", for Windows 8/8.1 32bit u take "Win8_32", for Windows 8/8.1 64bit u take "Win8_64".


11. When u find the correct inf file, you either double click on it or mark it and hit "Open":

Then you click "OK" here.


12. Then you get this window with a selection of drivers since this is a multi driver you get more then one, but scroll down in the window until you find "Qualcomm Atheros AR8161 PCI-E Gigabit Ethernet Controller (NDIS 6.30)" mark it and hit "Next":

  

13. Then you will get this "Update Driver Warning" that the driver ain't verified to the hardware bla bla bla, and it can be unstable or stop working completely which it won't because it works fine...

  

14. Then let Windows install the driver and you will get the message "Windows has successfully updated your driver software":

[!badge variant="light" icon=":heart:" text="Like"]
