---
title: rhodep Flashing Instructions 
description: Brought to you by IczYn 
---

<a href="#"><img align="center" img src="/assets/installation.png" /></a>

**Before start flashing.....** 
- Always have backup of your internal storage
----
**Clean flash:** 
- Download the ROM 
- Boot into bootloader mode
- fastboot reboot fastboot
- fastboot set_active a
- fastboot -w
- fastboot flash boot boot.img
- fastboot flash dtbo dtbo.img
- fastboot flash system system.img
- fastboot flash system_ext system_ext.img
- fastboot flash product product.img
- fastboot flash vendor vendor.img
- fastboot flash vendor_boot vendor_boot.img
- fastboot flash vbmeta vbmeta.img
- fastboot flash vbmeta_system vbmeta_system.img
- fastboot reboot

**Dirty flash:** 
- Download the ROM 
- Boot into bootloader mode
- fastboot reboot fastboot
- fastboot set_active a
- fastboot flash boot boot.img
- fastboot flash dtbo dtbo.img
- fastboot flash system system.img
- fastboot flash system_ext system_ext.img
- fastboot flash product product.img
- fastboot flash vendor vendor.img
- fastboot flash vendor_boot vendor_boot.img
- fastboot flash vbmeta vbmeta.img
- fastboot flash vbmeta_system vbmeta_system.img
- fastboot reboot
----
Download the rom from: [**Official Download Link for rhodep**](https://sourceforge.net/projects/projectmatrixx/files/Android-14/rhodep/)

----


