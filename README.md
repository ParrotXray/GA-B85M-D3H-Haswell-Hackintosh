# GA-B85M-D3H-Haswell-Hackintosh

## 🖥️Device

| Motherboard | GA B85M-D3H |
|------------|-------------------------------|
| CPU | Xeon E3-1230v3 |
| dGPU | AMD Radeon RX560 4G |
| RAM | 16GB |
| Audio | Realtek ALC892 |
| WIFI／Bluetooth | FV-T919(BCM94360cd) |
| Ethernet | Realtek® 8111F |
| BIOS Version | F12 |


## 📀System

### Noteice:
iGPU with Haswell cpu cannot be driven on macOS Ventura, dGPU needs to be installed
 
| ![alt text](Mac13.png) |
|------------|
| <a href="https://www.apple.com/tw/macos/macos-ventura-preview/"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/22/MacOS_logo_%282017%29.svg/512px-MacOS_logo_%282017%29.svg.png?20210723125421" height="32px"/>macOS Ventura 13.0 |
| <a href="https://github.com/dortania/build-repo/releases/tag/OpenCorePkg-effb8fe"><img src="https://raw.githubusercontent.com/acidanthera/OpenCorePkg/master/Docs/Logos/LogoApprox.svg" height="34px"/>Opencore 0.8.5-Dev-effb8fe |
| <a href="https://dortania.github.io/OpenCore-Install-Guide/extras/smbios-support.html#how-to-decide"><img src="https://aux.iconspalace.com/uploads/imac-icon-256.png" height="30px"/>MacPro 7.1 |
 
- Download:https://github.com/ParrotXray/GA-B85M-D3H-Haswell-Hackintosh/releases/tag/v0.8.5-Dev-effb8fe
 
| ![alt text](Mac.png) |
|------------|
| <a href="https://www.apple.com/tw/macos/monterey/"><img src="https://static.techspot.com/images2/downloads/topdownload/2021/10/2021-10-27-ts3_thumbs-36e.png" height="32px"/>macOS Monterey 12.6 |
| <a href="https://github.com/acidanthera/OpenCorePkg/releases/tag/0.8.4"><img src="https://raw.githubusercontent.com/acidanthera/OpenCorePkg/master/Docs/Logos/LogoApprox.svg" height="34px"/>Opencore 0.8.4 |
| <a href="https://dortania.github.io/OpenCore-Install-Guide/extras/smbios-support.html#how-to-decide"><img src="https://aux.iconspalace.com/uploads/imac-icon-256.png" height="30px"/>MacPro 7.1 | 
 
- Download:https://github.com/ParrotXray/GA-B85M-D3H-Haswell-Hackintosh/releases/tag/v0.8.4
## 💡Device status
### Works：
- [x] Graphics
- [x] USB
- [x] Sleep
- [x] WiFi
- [x] Speakers
- [x] Microphone
- [x] Bluetooth
- [x] Ethernet
- [x] AirDrop
### Unkown：
- [ ] Apple Services

## 🛠️Setting BIOS

#### CFG lock:
 
- The BIOS preset is unlocked

#### BIOS Features:

- Boot Mode Selection：`UEFI Only`

- Storge Boot Option Control：`UEFI Only`

#### Peripherals:

- XHCI Mode：`Enabled`

- Audio Controller：`Enabled`

- EHCI Hand-off：`Enabled`
 
- SATA Configuration/SATA Mode Selection：`AHCI`

- Super IO Configuration/Serial Port A：`Disabled`
 
#### Powrer Management:
 
- ErP：`Enabled`
