ThinkPad T430 - macOS Mojave Hackintosh
=======================================
This repository is licensed under the GNU GPL v2. Please read LICENSE.md for more information.
=======================================
### This is an EFI setup for running Apple's macOS Mojave on a ThinkPad T430
#### Warning #1: PLEASE! only use the setup in this repository on a ThinkPad with an Intel Core i5 3320M, 1366x768 screen, and Intel HD Graphics 4000. It would have to be modified to work on a different CPU, GPU or screen resolution, and I will not support those models for this reason.
#### Warning #2: PLEASE! generate your own serial number and UUID as per the iMessage guide on TonyMacX86. If you use my serial number & UUID, your iMessage and FaceTime will not work and it will just end up causing problems for both of us. So please, generate your own as per the guide.


## What works?
- WiFi (with a Broadcom card and IvyRa1n BIOS - macOS does not support Intel WiFi/BT, so don't ask)
- Bluetooth (with a Broadcom card and IvyRa1n BIOS - macOS does not support Intel WiFi/BT, so don't ask)
- Intel HD Graphics 4000 with full QE/CI (Quartz Extreme/Core Image) acceleration
- Keyboard
- Trackpoint (with proper acceleration & sensitivity)
- Trackpad (with two-finger scrolling in all 4 directions)
- SD card slot
- USB 3.0 & USB 2.0
- S3 sleep mode
- Native backlight adjustment
- FN keys
- iCloud, iMessage, FaceTime, App Store, etc (with proper config, of course. read the warnings above)
- Handoff & AirDrop (with properly working Bluetooth/WiFi)
- UEFI booting w/ minimal framebuffer glitches as the Intel graphics drivers initiatate
- Everything else

## What doesn't work?
- Nothing that I know of