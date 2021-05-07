# HackMini
ASROCK B460M Steel Legend Hackintosh

(-*-)

Here are the main specs:

• System-board: ASRock B460M Steel Legend

• CPU: Intel® Core™ i5-10600K

• GPU: iGPU

• Memory: Corsair Vengeance RGB PRO 64 GB (4x16 GB) DDR4 2666

• Add-on PCIE-Card 1: Sonnet Technologies USB3-4PM-E Allegro

• Add-on PCIE-Card 2: Inateck KU5211 (https://www.inateck.com/products/pcie-to-usb-3-2-gen-2-card-with-20-gbps-bandwidth-3-usb-type-a-and-2-usb-type-c-ports-ku5211-red)

• Storage: Sabrent 1tb nvme

• PSU: JLN-1600F 1600w

• Case: ionz KZ17 Micro ATX Cube

(-*-)

+Peripherals:

• Keyboards: Logitech Craft & Logitech K120.

• Mouses/Trackpad: Logitech M90, Kensington Orbit Trackball, Apple Magic Trackpad 2.

• External SoundCard: Creative Sound BlasterX G5

• Monitor: Samsung U32R592 32" Curved UHD 4K

(-*-)

What's Not working (or in working progress):
Motherboard's built-in usb 3.0 ports, Haven't tested SideCar and Airdrop yet.

(-*-)

Tools used to build EFI folder:

In the begining used @ducnm9 EFI, later used these tools to build/update EFI folder:

@Pavo-IM Opencore builder
@corpnewt MountEFI Commmand-line file and also his OCConfigCompare Command-line file, links below:

https://github.com/ducnm9/Hackintosh-Intel-i5-10400-Asrock-B460M-Steel-Legend

https://github.com/Pavo-IM/ocbuilder

https://github.com/corpnewt/OCConfigCompare

https://github.com/corpnewt/MountEFI

I had added also Gigabyte Titan Ridge 2, before I changed to Inateck KU5211, (I flashed card with custom, MacOS compatible firmware), And I had proper 40GBps Thunderbolt 3 (aswell was showing in System info under Thunderbolt).

Important NOTE: Please change MLB, SystemSerialNumber, SystemUUID into your Config.plist file, PlatformInfo section.

--- Last update on 5th of Feb, 2021:⤵


Still Shutdown won't work. Because of this problem I'm planning to sell this motherboard and replace this motherboard with MSI Z490m Gaming Edge Wifi and will be with same listed parts above.
