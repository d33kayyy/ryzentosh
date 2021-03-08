# Ryzentosh

My EFI configuration for **macOS Mojave** on Ryzen.

## Key specifications

| Component | Model |
| --------- | ----- |
| **CPU** | AMD Ryzen 5 3600 |
| **MOTHERBOARD** | MSI B450 Tomahawk Max |
| **GPU** | MSI Radeon RX 570 ARMOR 8G OC |
| **SSD (System)** | Samsung 860 Evo 250GB |
| **HDD (Data)** | Western Digital Caviar Blue 1TB |
| **ETHERNET** | _onboard_ |
| **AUDIO** | _onboard_ |
| **WIFI** | Broadcom BCM94360 |

## Compatibility checklist
- [x] Audio (Front panel and back)
- [x] USB (Front panel and back)
- [x] Ethernet
- [x] Sleep
- [x] Wifi
- [x] Bluetooth 
- [x] Proper GPU support
- [ ] Mic

### Not tested
* FileVault
* iServices

## OpenCore Configuration

I followed the [OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/prerequisites.html).

[OpenCore 0.5.9](https://github.com/acidanthera/OpenCorePkg/releases/tag/0.5.9)
### config.plist

_This setup was built a year ago that I don't remember anything anymore xD_

### Drivers

_This setup was built a year ago that I don't remember anything anymore xD_

### Kexts

* [AppleALC 1.5.0](https://github.com/acidanthera/AppleALC/releases/tag/1.5.0)
* [Lilu 1.4.5](https://github.com/acidanthera/Lilu/releases/tag/1.4.5)
* [RealtekRTL8111 2.2.2](https://github.com/Mieze/RTL8111_driver_for_OS_X/releases/tag/v2.2.2)
* [VirtualSMC 1.1.4](https://github.com/acidanthera/VirtualSMC/releases/tag/1.1.4)
* [WhateverGreen 1.4.0](https://github.com/acidanthera/WhateverGreen/releases/tag/1.4.0)

