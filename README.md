# Ryzentosh

My EFI configuration for **macOS Catalina (10.15.7)** on AMD Ryzen.

## Key specifications

| Component | Model |
| --------- | ----- |
| **CPU** | AMD Ryzen 5 3600 |
| **MOTHERBOARD** | MSI B450 Tomahawk Max |
| **GPU** | MSI Radeon RX 570 ARMOR 8G OC |
| **SSD (System)** | SSD Samsung 980 PCIe NVMe V-NAND M.2 2280 500GB |
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
- [ ] Bluetooth 
- [x] Proper GPU support
- [ ] Mic

### Not tested
* FileVault
* iServices

## OpenCore Configuration

I followed the [OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/prerequisites.html).

* [OpenCore 0.7.0](https://github.com/acidanthera/OpenCorePkg/releases/tag/0.7.0)

### ACPI

* [SSDT-EC-USBX-DESKTOP.aml](https://github.com/dortania/Getting-Started-With-ACPI/blob/b8e37ede5ec68165918cfd611e2afd3075f7fe27/extra-files/compiled/SSDT-EC-USBX-DESKTOP.aml)

### Kexts

* [AppleALC 1.6.1](https://github.com/acidanthera/AppleALC/releases/tag/1.6.1)
* [Lilu 1.5.3](https://github.com/acidanthera/Lilu/releases/tag/1.5.3)
* [RealtekRTL8111 2.4.2](https://github.com/Mieze/RTL8111_driver_for_OS_X/releases/tag/v2.4.2)
* [VirtualSMC 1.2.4](https://github.com/acidanthera/VirtualSMC/releases/tag/1.2.4)
* [WhateverGreen 1.5.0](https://github.com/acidanthera/WhateverGreen/releases/tag/1.5.0)
* [AirportBrcmFixup 2.1.2](https://github.com/acidanthera/AirportBrcmFixup/releases/tag/2.1.2) (needed this for Wifi)
