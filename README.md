
# Hackintosh Asus MQ3500QC-OLED995

This is EFI Folder for running Mac OS Ventura on AMD Laptop with APU Only (Nvidia 3050 not supported) on ASUS Vivobook MQ3500QC-OLED995

Tested Mac OS : Mac OS Ventura 13.5
## Laptop Spesification

**Processor:** AMD Ryzen 9 5900HX

**RAM:** 16 GB DDR4

**SSD:** NVME SK Hynix hfs512gde9x081n (Not Supported
)

**WIFI:** Intel Wifi 6 ax200

**Bluetooth:** Intel Bluetooth Hardware ID 0x8087, 0x0029


## Whats Working

- Boot
- Graphic Acceleration using AMD APU (Thanks to NootedRed by NootInc)
- Keyboard (VoodooPS2)
- All USB Port
- Touchpad & Gesture (Thanks to VoodoI2C by NootInc)
- Battery Management
- Webcam
- Audio (Internal Speaker & Audio Jack)
- HDMI


## Whats Not Working

- Sleep
- Shutdown (Auto restart)
- NVME drive (Not supported by current drive, must be replace using samsung 970 evo plus or wd blue, currently boot using external SSD)
- Mic (Need more try with another layout AppleALC)


## Installation

1. Disable Fastboot Option on Bios
2. Disable Secure Boot on Bios
3. Create USB Bootable Installer Disk Mac OS Ventura using tutorial on Website Apple https://support.apple.com/en-us/HT201372
4. Mount EFI Partition using Clover Configurator
5. Copy EFI Folder to EFI Parition.
6. Boot From USB
    
