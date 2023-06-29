# ASRock-B365M-ITX-Hackintosh
Hackintosh EFI for ASRock B365M-ITX/ac
## Software
|  macOS     |Monterey 12.6.5   |
| ------------- |-------------| 
|OpenCore    |  0.9.2  | 



## Hardware
| Motherboard   |ASRock-B365M-ITX/ac   |
| ------------- |-------------| 
|CPU    | i5-8400  | 
|RAM    | 8G*2 DDR4 2666  | 
|GPU    | RX6600XT  | 
|SSD    |   Crucial MX500 500GB       |
|Ethernet    | Intel I219-V  | 
|Wifi   | Dual Band 802.11ac WiFi AC 3168 | 
|Audio codec   | ALC887  | 


## Status

<summary><strong>What's working ✅</strong></summary>

- [x] OpenCore GUI
- [x] Window 10 dual boot
- [x] iGPU hardware acceleration
- [x] Ethernet
- [x] Sleep/Wake
- [x] USB Mapping
- [x] Audio
- [x] CPU temperature monitoring
- [x] System fan speed monitoring
- [x] GPU temperature monitoring
- [x] GPU fan speed control (fan start at 40ºC, stop at 35ºC, the end result is around 40ºC idle, same level as in Win. Credit: [6600XT-on-macOS-12-13-with-PowerPlayTable](https://github.com/perez987/6600XT-on-macOS-12-13-with-PowerPlayTable))


<summary><strong>What's not working ⚠️</strong></summary>



- [ ] Wifi/Bluetooth - get a Broadcom card for Wifi




<summary><strong>Untested ❔</strong></summary>


- [ ] iMessage, FaceTime, App Store, iTunes Store
- [ ] CPU power management
- [ ] NVMe drives - should be fine with nvme fix kext

## BIOS setting
### Enable:
* Above 4G Decoding
* XHCI Hand-off
* VT-d
* IGPU Multi-Monitor

### Disable:
* Fast Boot
* Secure Boot
* Intel SGX
* Intel Platform Trust
* CFG Lock
