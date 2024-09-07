# Ryzentosh

My EFI configuration for **macOS Ventura (13.6.7)** on AMD Ryzen.

## Key specifications

| Component | Model |
| --------- | ----- |
| **CPU** | AMD Ryzen 5 3600 |
| **MOTHERBOARD** | MSI B450 Tomahawk Max |
| **GPU** | GIGABYTE Radeon RX 6600 EAGLE 8G |
| **SSD (System)** | SSD Samsung 850 EVO 250GB |
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

* [OpenCore 0.8.9](https://github.com/acidanthera/OpenCorePkg/releases/tag/0.8.9)

### ACPI

* [SSDT-EC-USBX-DESKTOP.aml](https://github.com/dortania/Getting-Started-With-ACPI/blob/b8e37ede5ec68165918cfd611e2afd3075f7fe27/extra-files/compiled/SSDT-EC-USBX-DESKTOP.aml)

### Kexts

* [AirportBrcmFixup 2.1.6](https://github.com/acidanthera/AirportBrcmFixup/releases/tag/2.1.6) (needed this for Wifi)
* [AppleALC 1.7.9](https://github.com/acidanthera/AppleALC/releases/tag/1.7.9)
* [Lilu 1.6.3](https://github.com/acidanthera/Lilu/releases/tag/1.6.3)
* [RealtekRTL8111 2.4.2](https://github.com/Mieze/RTL8111_driver_for_OS_X/releases/tag/v2.4.2)
* [RestrictEvents 1.0.8](https://github.com/acidanthera/RestrictEvents/releases/tag/1.0.8)
* [VirtualSMC 1.3.0](https://github.com/acidanthera/WhateverGreen/releases/tag/1.3.0)

