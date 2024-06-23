## Summary

There are multiple methods of storing and loading game backups on PS2, but an internal hard drive will provide the highest compatibility and best loading times. The goal of this guide is to walk you through the steps of setting up a PS2 with an internal hard drive and pre-made FreeMcBoot memory card so that you can play PS2 game backups using OpenPS2Loader, known as OPL.

!!! note "Software modification"

    Using a FreeMcBoot (FMCB) memory card as an exploit is safe, easy, and requires no permanent modifications. When a PS2 turns on with a FMCB memory card inserted, it will automatically use the exploit and allow running homebrew including OPL (which can play game backups) without any further software modification. Removing the memory card before booting will revert it to stock.

!!! warning "Hardware modification"

    While hardware modification is not necessary for this guide, it is recommended for one minor upgrade to allow larger and more modern hard drives to be used. This modification is *only* performed on the internet adapter (not the PS2 itself) and is fairly straightforward.

This guide will cover how to format and partition a hard drive with a FreeMcBoot card, install game backups to the drive directly from PC, install a homebrew app (such as OPL if it is not already installed), and download game artwork to display in OPL.

Optionally, it is also possible to install the software exploit directly onto the hard drive (albeit with slightly slower boot time) to always boot into it without a memory card if desired. This exploit is called FreeHDBoot and should only be done after formatting the hard drive.

## Credits

This guide was written with a few key sources and guides either strictly followed but with the addition of images or otherwise serving as reference with some modifications to remove usage of obsolete software or simplify existing methods.

- [Blaine Locklair's The ULTIMATE Guide To Play PS2 Games From A HDD](https://www.youtube.com/watch?v=C02j3wTuJag)
- [Fin9ersMcGee's [Tutorial] The Great PS2 AIO Guide](https://www.psx-place.com/threads/tutorial-the-great-ps2-aio-guide.30219/)

## Requirements

- PS2 compatible with internal hard drive
    - All fat PS2s and certain slim models with hardware modification
- Official Sony PS2 internet adapter
    - For internal HDD expansion bay
- Internal hard drive
    - SATA (recommended, larger and more modern) or IDE
- If using SATA hard drive:
    - SATA upgrade kit for official Sony PS2 internet adapter
- Adapter for connecting internal hard drive to PC
- FreeMcBoot memory card
    - Can be purchased online, recommended to only buy official cards
- PC

!!! note "FreeMcBoot card"

    While it is possible to avoid buying or using FreeMcBoot (FMCB) card by flashing a FreeHDBoot image to a hard drive, this is not the recommended way to format or partition a drive. Cards are fairly cheap and easy to find online and will enable proper formatting of the drive on the PS2.

!!! warning "Gamestar network adapter"

    You may come across unofficial "network" adapters (without actual network functionality) such as Gamestar that already have SATA connectors and require no modification. These adapters greatly vary in quality, frequently break, and aren't compatible with virtual memory cards (VMCs) in OPL.

### Optional, but recommended

- USB thumb drive formatted to FAT32

## Getting Started

If you are planning to use a SATA hard drive it will be the single hardware modification required before starting this guide. The console mods wiki provides a [thorough text guide with diagrams here](https://consolemods.org/wiki/PS2:SATA_Board_for_LAN_Adapter), but in addition most kits will come with picture instructions for how to install the mod.

Once installed, you can begin the guide.

[**Begin guide: Format and partition hard drive**](../create-drive-partitions/) 