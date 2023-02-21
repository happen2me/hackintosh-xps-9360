# Hackintosh on XPS 13 9360 Developer Edition

## My Device Specs

**CPU:** Intel(R) Core(TM) i7-7500U CPU @ 2.70GHz

**Graphics:** 00:02.0 VGA compatible controller: Intel Corporation HD Graphics 620 (rev 02)

**Chipset**: 0VPVXX

- Motherboard details
    
    Handle 0x0002, DMI type 2, 15 bytes
    Base Board Information
    Manufacturer: Dell Inc.
    Product Name: 0VPVXX
    Version: A01
    Serial Number: /429HSF2/CNCMK0088DA027/
    Asset Tag: Not Specified
    Features:
    Board is a hosting board
    Board is replaceable
    Location In Chassis: Not Specified
    Chassis Handle: 0x0300
    Type: Motherboard
    Contained Object Handles: 0
    
    Handle 0x001C, DMI type 10, 6 bytes
    On Board Device Information
    Type: Video
    Status: Enabled
    Description: "Intel HD Graphics"
    
    Handle 0x0033, DMI type 41, 11 bytes
    Onboard Device
    Reference Designation:  Onboard IGD
    Type: Video
    Status: Enabled
    Type Instance: 1
    Bus Address: 0000:00:02.0
    
    Handle 0x0034, DMI type 41, 11 bytes
    Onboard Device
    Reference Designation:  Onboard LAN
    Type: Ethernet
    Status: Enabled
    Type Instance: 1
    Bus Address: 0000:00:19.0
    
    Handle 0x0035, DMI type 41, 11 bytes
    Onboard Device
    Reference Designation:  Onboard 1394
    Type: Other
    Status: Enabled
    Type Instance: 1
    Bus Address: 0000:03:1c.2
    

Touchpad: DLL075B

**RAM:** 16GB LPDDR3 (1866MHz)

**Storage:** ~~TOSHIBA THNSN5512GPUK 512GB PCIe m.2 SSD~~

- Replaced with WD Black SN750 NVMe

**Ports:** 1 x USB 3.0, 1 x USB 3.0 w/PowerShare, 1 x USB-C (Thunderbolt 3), SD card reader, headphone jack

**WLAN/Bluetooth:** ~~Qualcomm Killer 1535 802.11ac Wi-Fi; Bluetooth 4.1~~ 

- *replaced with* BCM94352Z_DELL (DW1560)

****Keyboard and Trackpad Connection Type****

Idk yet, now assume it to be ps/2

- Trackpad: `SMBus`
- Keyboard: `PS/2`

**Audio**

- Sunrise Point-LP HD Audio
├── Device ID: 0x9d71
├── Vendor: 0x8086
├── ACPI Path: \*SB*.PCI0.HDAS
├── PCI Path: PciRoot(0x0)/Pci(0x1f,0x3)
└── Codec: ALC3246
