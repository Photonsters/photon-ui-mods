# Photonsters Official UI Mod 
This is the Photonsters official UI (User Interface) modification for the original Anycubic Photon (Classic) printer. 

The default UI menu is hard to read on the small 2.8" touchscreen, compounded by a poor choice of low contrast cyan blue on white lettering. 

This modification addresses the default UI's primary deficiency. It replaces the default UI with a high contrast version to enhance legibility of the text and menu. It aims to provide a more legible and better user experience. 

This mod may also be deployed for all other Chitu-CBD mainboard based LCD printers with a 2.8" touchscreen. 

**Note that the Photon-S cannot use this UI mod because it is based on a completely different mainboard.** 

---

### Photonsters High Contrast Net UI (PHCN-UI) 

The PHCN-UI mod provides a clean and clear high contrast UI menu for the original Photon and other Chitu-CBD mainboard based printers with a 2.8" touchscreen. 

All icons are now in black & white, with black backgrounds for the firmware generated cyan coloured text. 

*This mod may also enable a hidden menu (depending on firmware version) that will allow users to network their printers via the embedded ethernet port on the printer's mainboard.*

The Photon UI is completely separate from the printer's firmware, installing this mod will make no changes to the firmware. The PHCN-UI is easily installed by just "printing" a single binary file. 

It is possible to revert to the original default UI at any time. The PHCN-UI mod package includes a copy of the default (original) UI. You may revert if you decide that this mod is not for you. 

---

**DISCLAIMER:** 
- This mod is made independently by the Photonsters Team and has no affiliations with Anycubic.
- This mod is officially cleared by Anycubic for installation and use and will not void the machine warranty.
- Depending on the installed firmware version, this mod may enable a hidden menu that allows network.  
- If the network feature is enabled, note that it is not covered by Anycubic and usage will be entirely at your own risk.
- This mod has been tested by the Photonsters Team and other Photon community members. 
- This mod is provided as-is, with no warranties of any kind by Anycubic or the Photonsters Team.
- Anycubic will give no support on issues arising from the use of this mod, open a issue [here](../../issues/new) instead.
- Installation and use of this mod is entirely at your own risk!

---

#### Installation

- [Download the latest PHCN-UI mod release here](#). 
- Extract the files to a good tested USB stick. 
- Insert USB stick into your printer. 
- Via touchscreen, select the `PHCNET_UI_2_8_xxxxxx.logo` file and "print" the file. 
- Wait for the beeps, press OK. 
- Now select the `PHCNET_UI_2_8_xxxxxx.bin` file and "print" it. 
- Wait for the beeps. Press OK. 
- That's it. You've enabled the new UI mod (and depending on your firmware, the hidden network features).  

Note:
As the UI mod makes no changes to the firmware or configurations, you do not need to relevel or reset Z=0.

---

#### Configuring the Network (unlocked hidden menu)
If your firmware version allows it, and you wish to use the network feature, continue with the following steps: 

- Via the touchscreen, access the network menu that was enabled by this PHCN-UI mod. 
- Switch the device to ethernet (Wireless/Ethernet button). 
- Enable the network (ON/OFF button). 
- Open the back access panel of your machine and connect a network cable to your switch or router. 
- The machine should acquire an IP address and show it on the touchscreen. 
- Using Chitubox v1.4.0 (or newer), you may now select the IP address of your Photon and send print files over or start a remote print. 






