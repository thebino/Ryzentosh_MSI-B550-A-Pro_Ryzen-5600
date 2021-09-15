# Hackintosh • Ryzen 5600X • B550-A Pro
[OpenCore](https://dortania.github.io/OpenCore-Install-Guide) bootloader configuration for Ryzen 5 5600X on a MSI B550 A-Pro.

![macOS](https://img.shields.io/static/v1?label=macOS&message=v11.4%20BigSur&color=blue&style=flat-square&logo=macOS)
![OpenCore](https://img.shields.io/static/v1?label=OpenCore&message=v0.7.2&color=19B3E7&style=flat-square&logo=apple)


## Status


## Hardware

| Name     |                             Model |
| :------- | --------------------------------: |
| CPU      |                     Ryzen 5 5600x |
| GPU      |               Asus GeForce GT 710 |
| RAM      | 64GB Kingston FURY Beast DDR4-3600|
| SSD      |         Samsung 970 Evo Plus NVMe |
| Board    |                    MSI B550 A-Pro |
| Ethernet |              RTL8111H Gigabit LAN |


## Firmware
| Driver       |         Version |
| :------------| --------------: |
| HfsPlus      | IM201 and IM161 |
| OpenRuntime  |           0.7.3 |


## Kexts

| Package                  | Version |
| :----------------------- | ------: |
| VirtualSMC               |   1.2.7 |
| Lilu                     |   1.5.6 |
| WhateverGreen            |   1.5.3 |
| AppleALC                 |   1.6.4 |
| RealtekRTL8111           |   2.4.2 |
| AirportBcrmFixup         |   2.1.3 |
| AppleMCEReporterDisabler |   1.2.0 |
| NVMeFix                  |   1.0.9 |


## SSDTs
| SSDT                     |
| :----------------------- | 
| [SSDT-CPUR](https://github.com/dortania/Getting-Started-With-ACPI/blob/master/extra-files/compiled/SSDT-CPUR.aml) |
| [SSDT-EC-USBX-DESKTOP](https://github.com/dortania/Getting-Started-With-ACPI/blob/master/extra-files/compiled/SSDT-EC-USBX-DESKTOP.aml) |


## config.plist

Based on [this guide](https://dortania.github.io/OpenCore-Install-Guide/AMD/zen.html)


#### SMBIOS

Selected: `MacPro7,1`

Please generate your own device uuid and board serial.
[Click here for details](https://dortania.github.io/OpenCore-Install-Guide/AMD/zen.html#platforminfo)


