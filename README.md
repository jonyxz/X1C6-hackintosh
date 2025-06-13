# MacOS for ThinkPad X1 Carbon Gen 6th [20KG]

This project provides a complete and functional macOS Sonoma `14.7.6` build for the ThinkPad X1 Carbon 6th Gen (model 20KG). It is based on the excellent guides from [tylernguyen](https://github.com/tylernguyen/x1c6-hackintosh) and [Rybo713](https://github.com/Rybo713/X1C6-macOS), with modified ACPI patches and updated kexts.

Using `MacbookPro15,2` SMBIOS

## My Specs
**Model:** X1C6 [20KG]

**Bios:** 1.65 Vanilla

**CPU:** 2.11GHz Intel i7-8650U (0x8086)

**GPU:** Intel UHD620 1536MB (0x5916)

**RAM:** 2133MHz Samsung 16GB Dual Channel LPDDR3

**Display:** 14" IPS Anti-Glare FHD Touch, 1920x1080, 60Hz

**Storage:** PCI-E x4 NVMe SSD 512GB

**Partition Type:** APFS

**Wifi:** Intel Wireless AC 8265

**Bluetooth:** Intel Wireless AC 8265

**Bootloader:** OpenCore v1.0.2


## Tested macOS Versions

- **macOS Sonoma**: 14.7.6

# What Works
- Audio
- Headphone Jack
- Keyboard
- Keyboard Brightness
- Power Management (CPUFriend)
- Battery Manager
- USB A Ports
- USB C Ports
- Trackpad, with full gestures
- Trackpoint
- Webcam
- Microphone
- Display Brightness
- Sleep 
- Wifi - Use [Heliport v1.5.0](https://github.com/OpenIntelWireless/HeliPort/releases/tag/v1.5.0)
- Bluetooth
- All FN Keys - Use [Thinkpad Assistant app](https://github.com/MSzturc/ThinkpadAssistant/releases)

# What doesn't work / Haven't tested
- Fingerprint sensor - Touch ID (It will never work) (Disabled in BIOS)
- HDMI - Haven't Tested
- Thunderbolt 3 - Haven't Tested
- microSD Card Reader - Haven't Tested
- Touch Screen - Doesn't work 

# Bugs
- Wake after Sleep

# Pre-Installation
1. Follow tylernguyen's [guide](https://tylernguyen.github.io/x1c6-hackintosh/).
2. Generate SMBIOS for `MacbookPro15,2`

## Credits
Special thanks to the following contributors for their invaluable resources:

- [tylernguyen](https://github.com/tylernguyen/x1c6-hackintosh)
- [benbender](https://github.com/benbender/x1c6-hackintosh)
- [zhtengw](https://github.com/zhtengw/EFI-for-X1C6-hackintosh)
- [Rybo713](https://github.com/Rybo713/X1C6-macOS)
