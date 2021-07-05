# Gigabyite H370M DS3H + i5-8500 Hackintosh

## System specifications
* Gigabyte H370M DS3H
* Intel i5-8500 Coffee Lake
* WD Black WDS500G3X0C NVMe SSD
* MSI Radeon RX 560 4GB
* [Fenvi T919 PCIe BCM94360CD](https://aliexpress.ru/wholesale?catId=0&initiative_id=SB_20210705092326&origin=y&SearchText=Fenvi+T919)
* macOS 11.4 Big Sur
## UEFI Firmware Settings
Disable VT-d, FastBoot, SGX, PTT
Enable Above 4G Decoding, USB XHCI

## Not Working
* Some usb 3 ports work as usb 2 ports only. It is known issue for Big Sur 11.4. The same works well for Big Sur 11.3
* DRM. Safari 14 and macOS 11, Big Sur are currently unsupported by WhateverGreen's DRM patches.

## References
[OpenCore Desktop Guide](https://dortania.github.io/OpenCore-Install-Guide/)
