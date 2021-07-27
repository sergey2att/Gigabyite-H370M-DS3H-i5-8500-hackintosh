# Gigabyite H370M DS3H + i5-8500 Hackintosh

![Gigabyite H370M DS3H + i5-8500 Hackintosh](Screenshot%202021-07-05%20at%2020.25.32.png?raw=true)

## System specifications
* Gigabyte H370M DS3H
* Intel i5-8500 Coffee Lake
* WD Black WDS500G3X0C NVMe SSD
* MSI Radeon RX 560 4GB
* [Fenvi T919 PCIe BCM94360CD](https://aliexpress.ru/wholesale?catId=0&initiative_id=SB_20210705092326&origin=y&SearchText=Fenvi+T919)
* macOS 11.4 Big Sur
## UEFI Firmware Settings
### Disable
* Fast Boot
* Secure Boot
* Intel SGX
* Intel Platform Trust
* CFG Lock (MSR 0xE2 write protection)(This must be off, if you can't find the option then enable AppleXcpmCfgLock under Kernel -> Quirks. Your hack will not boot with CFG-Lock enabled)
### Enable
* VT-x
* Hyper-Threading
* EHCI/XHCI Hand-off
* OS type: Windows 8.1/10 UEFI Mode
* DVMT Pre-Allocated(iGPU Memory): 64MB
* SATA Mode: AHCI

## References
[OpenCore Desktop Guide](https://dortania.github.io/OpenCore-Install-Guide/)
