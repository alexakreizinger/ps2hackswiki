# Burn discs with ESR

You can create self-booting game discs using the FreeDVDBoot ESR patcher. This lets you burn a PlayStation 2 game's `.iso` file onto a DVD, then play that game from your burned DVD—without modifying your PS2's hardware in any way.

!!! warning "Not all PS2s are compatible"

    The ESR patcher relies on [FreeDVDBoot](https://github.com/CTurt/FreeDVDBoot), which takes advantage of a hardware exploit in the PS2's DVD player. Since each SKU model of the PS2 uses a different version of the DVD player's firmware, not all SKU models are currently exploitable via FreeDVDBoot.

    For a current list of supported models, consult the [FreeDVDBoot compatibility list](https://www.psdevwiki.com/ps2/FreeDVDBoot_Compatibility_List).

## Compatible DVDs

You'll need to burn your ISO onto the right kind of DVD (most likely a DVD-R); not all DVDs will work. Reddit user u/theepiccarday808 has tested [several brands/types of discs](https://archive.is/Br9bH) and reported on the results of each.

It's not on this list, but I can personally confirm that [Verbatim DVD-R's "Life Series"](https://www.verbatim.com/prod/optical-media/dvd/dvd-recordable/dvd-dash-r-white-inkjet-printable-sku-95153/) discs in the orange packaging will work too.

## Compatible games

Certain games won't run on patched discs, or won't run very well. Refer to the [ESR game compatibility list](https://www.ps2-home.com/forum/page/esr-game-compatibility-list-1) for information about which games have been tested for compatibility.

## Tutorial

> *This guide is a paraphrased verison of [MrMario2011's YouTube tutorial](https://www.youtube.com/watch?v=_E_R8od6zdU).*

Creating a patched disc is a multi-step process. You'll need to [download the correct payload file](#download-payload-file), then [patch your `.iso`](#patch-iso), and then finally [burn your patched `.iso` to a disc](#burn-to-disc).

### Requirements

- [A compatible DVD](#compatible-dvds)
- [FreeDVDBoot ESR Patcher GUI](https://www.ps2-home.com/forum/viewtopic.php?f=123&t=9778)
- [ImgBurn](https://www.imgburn.com/index.php?act=download)
- [UltraISO](https://www.ultraiso.com/download.html) (only for games that are in `.bin + .cue` format—you'll need to use this tool to turn those files into an `.iso`)

### Download payload file

The ESR patcher requires an `.iso-image` payload file to create a patched disc that your PS2 will be able to read. Since different PS2 models have different DVD firmware versions, the correct payload file is dependent on your PS2's SKU.

!!! info

    Since your burned disc will use the payload you specify, each burned disc will only work on PS2s that are compatible with that payload version. For example, a disc burned using the "Hybrid" payload will work on a SCPH-700xx PS2 model, but not a SCPH-300xx PS2 model.

1. Navigate to the [FreeDVDBoot Compatibility List](https://www.psdevwiki.com/ps2/FreeDVDBoot_Compatibility_List).

1. Locate your PS2's SKU model, then check the `.iso-image` column for that model.

1. Click the text linked in that cell to download your payload file.

### Patch ISO

!!! info

    Patching an `.iso` will permanently alter that file. If you'd like to preserve your original, un-patched `.iso`, be sure to make a backup copy beforehand.

1. Get an `.iso` file.

    If you have a game in `.bin + .cue` format, follow MrMario2011's guide about using UltraISO to [convert your game](https://youtu.be/_E_R8od6zdU?t=423) to an `.iso` file.

1. Open the folder where you extracted the FreeDVDBoot ESR Patcher GUI, then navigate to the `/stuff` folder.

1. Copy your [payload file](#download-payload-file) into the `/stuff` folder.

1. Open the FreeDVDBoot ESR Patcher GUI (`FDVDB_ESR_Patcher.EXE`).

1. Click the **Select** button to locate and select your `.iso` file.

1. Open the **Payload** drop-down menu and select your payload.

1. Click **Patch**.

### Burn to disc

1. Load a blank DVD into your computer's disc drive.

1. Open ImgBurn and select **Write image file to disc**.

1. Select the folder icon next to "Source / Please select a file..." to open your file explorer, then locate and select your patched `.iso`.

1. Under **Settings**, open the **Write Speed** drop-down menu and choose the slowest write speed possible. (Smaller number = lower write speed. For example, if your options are 5x and 50x, select 5x.)

1. Click this button to start burning the `.iso` to your disc.

    ![a file icon with an arrow pointing to a disc](/assets/imgburn-button.png)

1. After ImgBurn is done burning the `.iso` to your disc, you can remove the disc from your computer and start using it in your PS2!
