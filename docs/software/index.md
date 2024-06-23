# Software

## OPL (Open Playstation Loader)

Notes: This may already be installed on the FMCB memory card, so only download if not previously loaded or updated.

- [OPL release v1.1.0](https://github.com/ps2homebrew/Open-PS2-Loader/releases/tag/v1.1.0)

## OPL File Managers

### Covered in this Guide

- [HDL Batch Installer](https://www.psx-place.com/resources/hdl-batch-installer.1173/)
- [OPL Manager](https://oplmanager.com/site/)
    - Requires .NET Install

### Command Line

- [PFS Batchkit Manager](https://www.psx-place.com/resources/pfs-batchkit-manager-2tb-support.1202/)

## Drive Formatters

- [GUIFormat](http://ridgecrop.co.uk/index.htm?guiformat.htm) to format USB thumb drives to FAT32

## Optional: FreeMCBoot Installer for FreeHDBoot

- [FreeMCBoot Installer](https://israpps.github.io/FreeMcBoot-Installer/test/8_Downloads.html)

## Obsolete + Not Recommended Software

| Software | Replacement | Recommendation |
| --- | --- | --- |
| WinHIIP or Windows HDL Image Install Program | HDL Batch Installer | The [official download page](https://www.psx-place.com/resources/obsolete-winhiip-by-gadgetfreak.666/) is marked obsolete along with warnings for issues with OPL, drives larger than 1TB, and a 255 game limit. |
| HDL BATCH | HDL Batch Installer | "Uses an older version of HDL-Dump" - [source](https://israpps.github.io/HDL-Batch-installer/why_hdlbinst_is_better.html) |
| HDL Dump | HDL Batch Installer | "Uses an older version of HDL-Dump" - [source](https://israpps.github.io/HDL-Batch-installer/why_hdlbinst_is_better.html) |
| HDL or HD Loader | OPL | Obsolete with lower compatibility compared to OPL. |
| HDDRawCopy | HddManager on PS2 | Used to install pre-made disc images. However, these disc images are created from drives that may have differing disk geometry from the one you are using, so it is recommended to instead use uLaunchELF to format and create needed partitions. |