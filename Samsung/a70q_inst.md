----
title: a70q Flashing Instructions
description: Brought to you by DynamicPanda
----

<a href="#"><img align="center" img src="/assets/installation.png" /></a>

**Before start flashing.....**

- Always have backup of your internal storage
- Use recovery which is inside the rom zip file. 
- For vanilla variant, if u need gapps, [**Use MindTheGapps14**] (https://github.com/MindTheGapps/14.0.0-arm64/releases/tag/MindTheGapps-14.0.0-arm64-20231025_234300)


----

## RecoveryFlashing
- Extract the rom zip file and convert the recovery.img to recovery.tar using 7zip or any other method u want.
- If Flashing first time, then flash recovery.tar in the AP section of odin, then flash vbmeta.img. If not flashing recovery for the first time, then just flash recovery.tar and reboot to recovery


## Vanilla variant

**Clean flash:**
- Download the ROM and Gapps (MindTheGapps14)
- Boot into recovery
- Wipe Cache,System,Data
- Flash the ROM using adb or sdcard, After that flash gapps
- reboot to system


**Dirty flash:**
- Download the ROM
- Boot into recovery
- Wipe Cache
- Flash the ROM 
- Flash the Same Gapps again
- Reboot To System

----

----
Download the rom from: [**Official Download Link for a70q**](https://sourceforge.net/projects/projectmatrixx/files/Android-14/a70q/)

----
