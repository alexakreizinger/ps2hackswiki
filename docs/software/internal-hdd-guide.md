## Summary

There are multiple methods of storing and loading game backups on PS2, but an internal hard drive will provide the highest compatibility and best loading times. The goal of this guide is to walk you through the steps of setting up a PS2 with an internal hard drive so that you can play PS2 game backups using OpenPS2Loader, known as OPL.

!!! warning "Hardware modification"

    While hardware modification is not necessary for this guide, it is recommended for one minor upgrade to allow SATA (which are larger and more modern than IDE) hard drives to be used. This modification is *only* performed on the internet adapter (not the PS2 itself) and is fairly straightforward.

This guide will cover how to properly format and partition a hard drive, install game backups to the drive directly from PC, install a homebrew app (such as OPL if it is not already installed), and download game artwork to display in OPL.

Optionally, it is also possible to install the software exploit directly onto the hard drive (albeit with slightly slower boot time) to always boot into it without a memory card if desired. This exploit is called Free HDBoot and should only be done after formatting the hard drive.

## Credits

This guide was written by following some excellent existing guides and cross referencing updated information from dedicated and knowledgeable PS2 communities.

- [Blaine Locklair's The ULTIMATE Guide To Play PS2 Games From A HDD](https://www.youtube.com/watch?v=C02j3wTuJag)
- [Fin9ersMcGee's [Tutorial] The Great PS2 AIO Guide](https://www.psx-place.com/threads/tutorial-the-great-ps2-aio-guide.30219/)
- [PSX-Place](https://www.psx-place.com/)
- [r/ps2](https://www.reddit.com/r/ps2/)
- [PS2-Home](https://www.ps2-home.com/forum/app.php/portal)

## Requirements

- PS2 compatible with internal hard drive
    - All fat PS2s and certain slim models (SCPH-700XX) with hardware modification
- Official Sony PS2 internet adapter
    - For internal HDD expansion bay
- Internal hard drive under 2TB
    - SATA (recommended) or IDE
- If using SATA hard drive:
    - SATA upgrade kit for official Sony PS2 internet adapter
- Adapter for connecting internal hard drive to PC
- PC

!!! info "Hard drives larger than 2TB"

    While the method in this guide is limited to drives under 2TB, there is an alternative, less documented method that allows drives larger than 2TB to be used. This guide will not provide instructions on how to set this up, but instead [summarizes its pros and cons and provides links to other guides on this page](../grimdoomer-OPL-fork/).

!!! note "SATA vs IDE hard drives"

    In the years following the PS2's release SATA drives replaced IDE drives, but the official PS2 network adapter (which mounts a hard drive internally so it can be used in the expansion bay) was only released with IDE connectors. This guide recommends SATA hard drives as they are much larger, cheaper, and easier to find, but note that this will require installing a SATA connector on the network adapter using a **SATA network adapter upgrade kit**. A SATA drive and upgrade kit will provide larger storage for a lower price.

!!! warning "Gamestar network adapter"

    You may come across unofficial "network" adapters (without actual network functionality) such as Gamestar that already have SATA connectors and require no modification. These adapters greatly vary in quality, frequently break, and aren't compatible with virtual memory cards (VMCs) in OPL.

### Optional, but recommended

- USB storage device formatted to FAT32

## Getting Started

If you are planning to use a SATA hard drive, you must first install a SATA connector on your official PS2 network adapter using a SATA upgrade kit. This will be the single hardware modification required before starting this guide. The console mods wiki provides a [thorough text guide with diagrams here](https://consolemods.org/wiki/PS2:SATA_Board_for_LAN_Adapter), but in addition most kits will come with picture instructions for how to install the mod.

Once installed, you can begin the guide.

[**Begin guide: Choose internal HDD compatible exploit**](../internal-hdd-exploits/) 