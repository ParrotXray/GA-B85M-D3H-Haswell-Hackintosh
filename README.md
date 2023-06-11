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

| ![alt text](Mac14.png) |
|------------|
| <a href="https://www.apple.com/tw/newsroom/2023/06/macos-sonoma-brings-new-capabilities-for-elevating-productivity-and-creativity/"><img src="https://miro.medium.com/max/1200/0*kIZGmKka4RBS9R2D.png" height="32px"/>macOS Sonoma beta 1 |
| <a href="https://github.com/dortania/build-repo/releases/tag/OpenCorePkg-408f000"><img src="https://raw.githubusercontent.com/acidanthera/OpenCorePkg/master/Docs/Logos/LogoApprox.svg" height="34px"/>Opencore 0.9.3-Dev-408f000 |
| <a href="https://dortania.github.io/OpenCore-Install-Guide/extras/smbios-support.html#how-to-decide"><img src="https://aux.iconspalace.com/uploads/imac-icon-256.png" height="30px"/>MacPro 7.1 |

| ![alt text](Mac13.png) |
|------------|
| <a href="https://www.apple.com/tw/macos/macos-ventura-preview/"><img src="https://i.pcmag.com/imagery/reviews/04iuiyBZ61YPzdVS4GfRYKM-29.fit_scale.size_760x427.v1666629922.png" height="32px"/>macOS Ventura 13 + |
| <a href="https://github.com/acidanthera/OpenCorePkg/releases/tag/0.9.2"><img src="https://raw.githubusercontent.com/acidanthera/OpenCorePkg/master/Docs/Logos/LogoApprox.svg" height="34px"/>Opencore 0.9.2 |
| <a href="https://dortania.github.io/OpenCore-Install-Guide/extras/smbios-support.html#how-to-decide"><img src="https://aux.iconspalace.com/uploads/imac-icon-256.png" height="30px"/>MacPro 7.1 |

| ![alt text](Mac.png) |
|------------|
| <a href="https://www.apple.com/tw/macos/monterey/"><img src="https://static.techspot.com/images2/downloads/topdownload/2021/10/2021-10-27-ts3_thumbs-36e.png" height="32px"/>macOS Monterey 12.6 |
| <a href="https://github.com/acidanthera/OpenCorePkg/releases/tag/0.9.2"><img src="https://raw.githubusercontent.com/acidanthera/OpenCorePkg/master/Docs/Logos/LogoApprox.svg" height="34px"/>Opencore 0.9.2 |
| <a href="https://dortania.github.io/OpenCore-Install-Guide/extras/smbios-support.html#how-to-decide"><img src="https://aux.iconspalace.com/uploads/imac-icon-256.png" height="30px"/>MacPro 7.1 | 
 
- <a href="https://github.com/ParrotXray/GA-B85M-D3H-Haswell-Hackintosh/releases/tag/v0.9.3-Dev-408f000"><img src="https://aux.iconspalace.com/uploads/downloads-folder-icon-256.png" height="32px">Click me to download EFI file

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
- [x] Apple Services

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
