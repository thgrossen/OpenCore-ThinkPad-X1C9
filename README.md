# macOS on ThinkPad X1 Carbon Gen 9

Work in progress to run macOS on ThinkPad X1 Carbon Gen 9 using OpenCore EFI.

At this time, this config allows to boot and install macOS Monterey. USB, Audio, Trackpad, sleep, etc. have not yet been patched.


## Important note
The ThinkPad X1C9 features a Intel Tiger Lake 11th Gen processor (i7 in my case) which is **not** supported by macOS.
Although this OpenCore config spoofs the CPU to a 10th Gen CPU, be aware that there is no way to have GPU grafic acceleration.


## Usage
Generate your own platforminfo and SMBIOS, and update config.plist.


## Bios settings
- Load defaults
- Disable Secure boot
