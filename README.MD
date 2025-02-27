## Lenovo ThinkCentre M720Q Hackintosh (2025)
I am using a Lenovo M720Q with EFI (OpenCore 1.0.3), which allows me to install macOS on this device. The version of macOS I am using is 15.3.1, which is fully compatible with this configuration. The integrated graphics on my computer can output display through two interfaces, such as HDMI and DisplayPort, without issues. I do not use a discrete graphics card, so this computer relies solely on integrated graphics. Both Bluetooth and Wi-Fi features are working normally after I performed the installation. Below is a brief explanation of the specifications of my hardware:

## Specification
|   Component   |   Model   |
| ------ | ------ |
| CPU | Intel i5-9400T - 6 cores, 3.40GHz |
| Motherboard | Intel B360 |
| RAM | 16GB DDR4-2666 (8G*2) |
| Audio Chipset | ALC233VB2 |
| iGPU | Intel® UHD Graphics 630 (DP, HDMI) |
| OS Disk |  INTEL SSDPEKNW512G8L - 512 GB |
| WIFI | Intel Dual Band Wireless-AC 8265, 802.11ac Dual Band 2x2 Wi-Fi® + Bluetooth 4.2, M.2 Card |


macOS version: 15.3.1
OpenCore version: 1.0.3
SMBIOS : Macmini8,1

![About Mac](/screenshots/img1.png)
![About Mac](/screenshots/img2.png)

## All Work
- CPU ✅
- Dual monitors (Displayport & HDMI) ✅
- Audio (ALC235) (alcid:13,18,21,36 OK) ✅
- Ethernet ✅
- USB ✅
- Wifi (with heliport, Because the Intel Wi-Fi doesn't work like in previous versions, in Sequoia (15.3.1), it requires HeliPort to make it function properly) ✅ 
- Bluetooth ✅
- App store, iCloud, iMessage, iTunes, FaceTime, etc ✅
- Sleep, Wakeup, Shutdown, Restart ✅

## Not Work
- Airdrop, Hand-off, Sidecar
- Iphone Mirroring (Need T2 Chip)


### Notes
> Don't forget to install HeliPort after the installation is complete so that the Wi-Fi works properly.