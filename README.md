# Msi-H510M-A-PRO-i5-10500-Opencore-hackintosh-bigsur,or monterey
Hackintosh  for msi h510  motherboard  and i5 10500 with  UHD 630 


OpenCore Version: v0.8

macOS Version: Monterey(12.6.1)

## Main Specification

| Component   | Model                                                        |
| ----------- | ------------------------------------------------------------ |
| CPU         | Intel Core i5-10500 6-Cores And 12hreads @ 3.1Hz<br/>（**Comment Lake** CPUs Are Supported，**Celeron** and **Pentium** CPUs Are Not Supported） |
| MotherBoard | MSI H510M A-PRO<br/>    |
| GPU         | intel uhd graphics 630<br/>（Recommended Use GPUs : **Nvdia GTX 6XX , 7XX** And **Radeon RX 5XX** Etc)  <br/> If you are using external GPU then you don't have to patch HDMI ports |
| SSD         | 256G SATA (you can use  nvme drives )
| Ethernet    | On-board Intel I219V V10 1G<br/>

## Installation

1. Create [macOS installer](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/mac-install.html#downloading-macos-modern-os).

2. Use [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) to generate your SMBIOS data for your `config.plist`. 

3. For  installing the macos use the installer EFI (if you use other than  you will not get any display out )
4. Use pacth guide to patch the dispay  .

## Working

- On-board Ethernet
- iMessage, iCloud, FaceTime, App Store, Apple Music
- All USB ports
- Wifi (intel card )

## Not Working

- AirDrop, Sidecar
- Unlock with Apple Watch
- Bluetooth

# Display Patch
- Use patch manual to patch the display (HDMI port ) Thanks to wtsjw 


To Get Started, We're Gonna Need **OpenCore 

 Add The [Resources](https://github.com/acidanthera/OcBinaryData) To EFI/OC

- Add The [Resources](https://github.com/acidanthera/OcBinaryData) to EFI/OC

- Add **OpenCanopy.efi** To EFI/OC/Drivers

  *Note: OpenCanopy.efi Must Be From The Same Build As Your OpenCore Files, As Mismatched Files Can Cause Boot Issues.
