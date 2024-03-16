---
title: Realme GT 5G (cupidr)
description: Brought to you by MNoxx74
---
<a href="#"><img align="center" img src="/assets/installation.png" /></a>

**Please note that RUI 4.0 EX01 firmware is included in these builds**

**First Time Install / Clean Flash from RUI/Other Custom ROM**

1. Be on RUI 4.0 and have an unlocked bootloader
2. Download recovery imgs for your device from [HERE](https://sourceforge.net/projects/projectmatrixx/files/Android-14/cupidr/recovery/)
3. Reboot to bootloader
4. Extract Matrixx recovery zip file
5. *fastboot flash dtbo dtbo.img
   fastboot flash vendor_boot vendor_boot.img
   fastboot flash boot boot.img
   fastboot reboot recovery*
6. While in recovery navigate to Factory reset -> Format data/factory reset and confim to format the device.
7. When done formatting, go back to the main menu and then navigate to Apply update -> Apply from ADB
8. adb sideload rom.zip (replace "rom" with actual filename)
9 (optional). Reboot to recovery to sideload any add-ons (e.g magisk)
10. Reboot to system & Enjoy

**Update**
1. Reboot to recovery
2. While in recovery, navigate to Apply update -> Apply from ADB
3. adb sideload rom.zip (replace "rom" with actual filename)
4. Reboot to system & Enjoy

**OTA**
1. Download the update from Updater
2. Install it.
3. Reboot and Enjoy

----
ROM Download Link : [**Official Download Link for cupidr**](https://sourceforge.net/projects/projectmatrixx/files/Android-14/cupidr/)

----