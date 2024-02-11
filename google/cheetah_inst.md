---
title: cheetah Flashing Instructions
description: Brought to you by Pyrtle93
---

<a href="#"><img align="center" img src="/assets/installation.png" /></a>

**Before start flashing.....**

- Always have backup of your internal storage
- Get ready to provide logs/crash url and steps to reproduce the bug along with bug reports

----

**Clean flash:**
- Be on latest firmware
- fastboot -w update .zip 
- Reboot to System

**Root:** same process for clean/dirty
- Download and Install Magisk apk
- Unzip the factory image file, In the same folder you’ll get another zip file, unzip it too to get the init_boot.img file and copy it to your Pixel device.
- Patch init_boot.img file, Open Magisk app on your device, tap on install and tap again on “Select and Patch a file” and browse the init_boot.img file you’ve just copied. It will patch the file and save it in the same folder. Now you’ve to transfer patched init_boot.img file to your PC to flash it using an adb command.
- Reboot the device in Fastboot
- On your PC, open the plaform tools folder, hold the Windows button and right click in the folder and select open command here. Type the following commands to flash the patch boot file, below is an example; fastboot flash init_boot C:\Users\Imran\Desktop\Pixel 7 Root\platform-tools_r33.0.3-windows\platform-tools\magisk_patched-25200_xgjAS.img
- You can verify root access by downloading the root checker app from the Google Play Store.

**Dirty flash:**
- Be on latest firmware
- fastboot update .zip 
- Reboot to System

----
Download the rom from: [**Official Download Link for cheetah**](https://sourceforge.net/projects/projectmatrixx/files/Android-14/cheetah/)

----
