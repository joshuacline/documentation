# Feature Overview
- Windows To Go (USB) ⬦ Windows To Stay (SSD) ⬦ Lightweight ~60KB footprint
- Create a secure boot compatible vhdx-boot (OS Boot) or deployment (Windows Setup) disk
- Provided with a Windows installation source, create a simple yet robust recovery environment
- Import Windows installation media and boot media from an iso or disc
- Conversion of wim/vhdx ⬦ Deploy or capture Windows via virtual disk image
- Create a backup of a Windows installation using the vhdx-to-wim option when booted into recovery.
- Perform an in place upgrade to a Windows installation using the wim-to-vhdx option when booted into recovery.
- Requirements: USB or SSD disk ⬦ UEFI compatible bios ⬦ Windows disc or ISO ⬦ english host OS

![Alt text](https://raw.githubusercontent.com/joshuacline/documentation/main/deploy/png/portable.png "portable")
![Alt text](https://raw.githubusercontent.com/joshuacline/documentation/main/deploy/png/bootcreatorlog.png "bootcreatorlog")

# Procedure
- 1. Extract the .zip into a new folder.
- 2. Insert a Windows disc or mount a Windows ISO.
- 3. Open deploid.cmd, then import the Windows installation media and boot media by pressing (-) and (+).
- 4. Convert the Windows installation media (WIM) to a virtual hard disk image by pressing (C).
- 5. Create the bootable disk by pressing (G). 

# WinPE Recovery

![Alt text](https://raw.githubusercontent.com/joshuacline/documentation/main/deploid/png/recovery.png "recovery")

- Change Boot Order

![Alt text](https://raw.githubusercontent.com/joshuacline/documentation/main/deploid/png/booteditor.png "booteditor")
![Alt text](https://raw.githubusercontent.com/joshuacline/documentation/main/deploid/png/bootmenu.png "bootmenu")

# Settings
- Text size can be adjusted by holding down the ctrl key and scrolling the mouse wheel
- Update Recovery ⬦ Program ⬦ Test a program update until next reboot
- Ability to hide the vhdx host partition is available when booted into recovery

![Alt text](https://raw.githubusercontent.com/joshuacline/documentation/main/deploid/png/settings.png "settings")
