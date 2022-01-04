# Asus-Prime-Z490-A-OpenCore-Hackintosh
Asus Prime Z490-A-OpenCore-Hackintosh

**Specs** 
* Asus Prime Z490-A
* i9-10850K + NZXT Kraken X73 AIO 360 Cooler 
* Rx 580 MK2 
* 64G (3600 G.Skill RAM)
* 1TB S11 Pro NVME SSD (boot drive)
* 1TB Sandisk SATA SSD (Data)
* BCM4360CS2 Wireless Card (Work OBO) + M2.Adapter [Really cheap combination]

**What Work** 
* All iServices(iCloud/iMessage etc.) 
* Audio via 3.5mm port 
* Bluetooth/Wireless
* GPU Acceleration/Encode/Decode HVEC 
* DRM (watch AppleTV+/Amazon Prime/Netflix) 

**What Not Work** 
* laggy Apple MagicTrackpad 2 (Connecting directly with USB seems fine? Any help will highly appreciated.)

**Change log** 

2021-12
* Finished update OC to 0.7.6 (Make sure do a NVRAM reset, otherwise the Hackintool might detect the wrong/older version)
* Re-mapped the USB ports(Due to change the Wirless card from BCM4360CD with PCI-E adapter to use BCM4360CS2 with M2.Adapter), saved one Internal USB connector for other use. (might add a ThunderBolt card?) 
* Update some corresponding Kext and also did my best to optimize the Config to help future OC upgrade. 

2021-10-25
* Updated the OpenCore version to 0.7.4
* Fixed reboot issue by removing all the FakePCIID Kext
* Updated to MacOS 12 Monterey 
* Everything else seems working fine so far
