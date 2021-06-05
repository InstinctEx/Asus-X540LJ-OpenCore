# Asus-X540LJ-Hackintosh-OpenCore
Asus X540LJ Hackintosh working OpenCore 0.6.8 EFI with macOS Big Sur 11.2.3

# Asus Vivobook X540LJ
- **Bootloader:** OpenCore 0.6.8
- **macOS:** 11.2.3 Big Sur

# Specifications:

- **MainBoard:** Asus X540LJ.
- **Processor:** Intel Core i3-4005U @ 1.7GHz (Haswell)
- **RAM:** 8GB DDR3 1600mhz (Duel channel)
- **Graphic:** 
  + Intel HD5400
  + NVIDIA GeForce 920M 2GB
- **Network:**
  + **Wifi:** Atheros AR9565
  + **Ethernet:** Realtek RTL810xE
- **Audio:** Realtek ALC255 (layout-27)
- **Touchpad:** ELAN 1100 (I2C)
- **SD Card Reader** Realtek RTS5286
- **Storage**: SSD 500GB

# WORKING:
- [x] Power Management
- [x] Intel HD Graphics 5400
- [x] Sound **(Internal Speaker and Headphone working)**
- [x] Mic **(Internal and External both working)**
- [x] Wifi
- [x] Bluetooth
- [x] SD Card Reader
- [x] Ethernet
- [x] Adjust brightness 
- [x] USB 2.0 and 3.0
- [x] Trackpad **(All gestures supported)**
- [x] Sleep  **(working while power adapter is not connected and using battery)**
- [x] Battery Stat 
- [x] Tempareture Monitor 
- [x] Apple Store 
- [x] iCloud 
- [x] Fn feature    **(not all button works)**

# Not WORKING:
- [ ] Nvidia 920M GPU   **(will never work due to how MacOS handles optimus laptops)**


# BIOS Settings:
- **Vt-d:** Enable
- **DVMT Pre-Allocated :** 64M

# Installation:
- Change the BIOS settings.
- Just put this EFI to your USB EFI partition.
- Install macOS Big Sur.
- No need to install any additional kext to macOS extention. All driver will be loaded automatically.
- After install mount the USB EFI and copy this to your HDD EFI.
- Change the serial numbers and other things. You can find the tutorial from [here.](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/broadwell.html#platforminfo)

# Bluetooth fix:
- To get bluetooth work, you have to put your laptop to sleep mode for once.


## Credits
@shammu2bd for base files
