# Photonsters Official UI Modifications 

These are the Photonsters official UI (User Interface) modifications for the original Anycubic Photon (Classic) printer. 

The default UI menu is hard to read on the small 2.8" touchscreen, compounded by a poor choice of low contrast cyan blue on white lettering. 

These modifications address the default UI's primary deficiency. They replace the default UI with a high contrast version to enhance legibility of the text and menu. The primary aim is to provide a more legible and better user experience. Future versions may include more optimisations, personalisation, and alternate colour schemes. 

These UI mods may also be deployed for all other Chitu-CBD mainboard based LCD printers with a 2.8" touchscreen. 

**Note that the Photon-S cannot use these UI mods because it is based on a completely different mainboard.**

不適用於Photon-S！
Photon-Sでは動作しません。
Photon-S에서 작동하지 않습니다!
ไม่ทำงานกับ Photon-S!
Не работает для Photon-S!
Ne fonctionne pas pour Photon-S!
Funktioniert nicht für Photon-S!
Non funziona per Photon-S!
Não funciona para o Photon-S!
Non opus Photon-S! 

---

### Photonsters High Contrast Net UI (PHCN-UI) 

This is the first of the official Photonsters UI modifications. The PHCN-UI mod provides a clean and clear high contrast UI menu for the original Photon (and other Chitu-CBD mainboard based printers with a 2.8" touchscreen). 

With this mod, icons are now in black & white, with black backgrounds for the firmware generated cyan coloured text. 

*This mod may also enable a hidden menu (depending on firmware version) that will allow users to network their printers via the embedded ethernet port on the printer's mainboard.*

The Photon UI layer is completely separate from the printer's firmware and configurations layers, installing this mod is safe and will make no changes to the printer's firmware or configurations. It is also entirely possible to revert to the original default UI at any time. 

The PHCN-UI mod is easily installed by just "printing" two small files. 

*Confirmed working with most firmwares including the official AA enabled firmware v4.2.17*

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

- [Download the latest PHCN-UI mod release here](https://github.com/Photonsters/photon-ui-mods/blob/master/PHCN-UI/PHCNET_UI_2_8_190513.zip). 
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
- Some Info on Modding the photon back grill and connecting to the photon [here - FB Post](https://www.facebook.com/groups/AnycubicPhoton/permalink/1651711838306785/)






