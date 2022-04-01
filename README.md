# Asus-Prime-Z490-A-OpenCore-Hackintosh
Asus Prime Z490-A-OpenCore-Hackintosh

**Specs** 
* [Asus Prime Z490-A](https://amzn.to/3GvvPKj)
* [i9-10850K](https://amzn.to/3FyxQns) + [NZXT Kraken X73 AIO 360 Cooler ](https://amzn.to/3GuFP6k)
* [Rx 580 MK2](https://amzn.to/3rnUyK7) 
* [64G (G.Skill Ripjaws V Series 3600 CL16 )](https://amzn.to/33vPlaN)
* [1TB S11 Pro NVME SSD](https://amzn.to/3I3TiT6) (boot drive)
* [1TB Sandisk SATA SSD](https://amzn.to/3rDMF3t) (Data)
* [BCM43602CS Wireless Card (Work OBO)](https://amzn.to/3nswFjw) + [M2.Adapter](https://amzn.to/3fqQHX3) [Relative cheaper combination]

**What Work** 
* All iServices(iCloud/iMessage etc.) 
* Audio via 3.5mm port and HDMI/DisplayPort 
* Bluetooth/Wireless
* GPU Acceleration/Encode/Decode HVEC 
* DRM (watch AppleTV+/Amazon Prime/Netflix) 

**What Not Work** 
* laggy Apple MagicTrackpad 2 (Connecting directly with USB seems fine? Any help will highly appreciated. Also, it might be an issue with MacOS, as I have seem many real Macbook user have experiened similar issue from varies forums)

**Change log** 

2021-3-31 (Upgraded to 12.3.1)
* removed dk.e1000 flag; used the PIC-E device property for the ethernet port;

2021-12
* Finished update OC to 0.7.6 (Make sure do a NVRAM reset, otherwise the Hackintool might detect the wrong/older version)
* Re-mapped the USB ports(Due to change the Wirless card from BCM4360CD with PCI-E adapter to use BCM4360CS2 with M2.Adapter), saved one Internal USB connector for other use. (might add a ThunderBolt card?) 
* Update some corresponding Kext and also did my best to optimize the Config to help future OC upgrade. 

2021-10-25
* Updated the OpenCore version to 0.7.4
* Fixed reboot issue by removing all the FakePCIID Kext
* Updated to MacOS 12 Monterey 
* Everything else seems working fine so far
