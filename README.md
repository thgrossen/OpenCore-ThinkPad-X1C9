# macOS on ThinkPad X1 Carbon Gen 9

Work in progress to run macOS on ThinkPad X1 Carbon Gen 9 using OpenCore EFI.

## Important note
The ThinkPad X1C9 features an Intel Tiger Lake 11th Gen processor (i7 in my case) which is not supported by macOS.
Although this OpenCore config spoofs the CPU to a 10th Gen CPU, be aware that there is no way to have GPU graphics acceleration.


## Progress
Date | Feature | Status
-|-|-
2022-03-23 | Custom USB mapping | Fixed
2022-03-22 | Bluetooth | Fixed
2022-03-22 | Shutdown | Fixed
2022-03-22 | Battery Status | Fixed
2022-02-02 | Initial config | macOS Monterey installed

OpenCore 0.7.7 (DEBUG)\
macOS Monterey 12.1 (21C52)

## What works (on March 23, 2022)
- All USB Type C (3.1 & 2.0)
- All USB Type A (3.0 & 2.0)
- Wifi
- Bluetooth
- Battery status
- Shutdown/Restart
- TrackPoint


## Usage
Generate your own platforminfo and SMBIOS, and update config.plist.


## Bios settings
- Load defaults
- Disable Secure boot
