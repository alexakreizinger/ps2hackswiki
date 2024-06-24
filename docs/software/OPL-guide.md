# Setting up and using OPL

OPL documentation across the web is very thorough, so this guide will mainly compile those resources into categories.

!!! warning "PS2-Home forum"

    Many of these guides live on a forum called PS2-Home. You may find that the links will show a 503 error or display an IP ban notification. This does not mean the forum is down, but that your IP has been blocked from accessing the site. You may be able to access the page with a VPN, by using a different internet connection, or on cellular data, but in case none of these options work web archive mirrors of these pages will be provided as well. Be sure to check you are on the latest mirror of these pages.

## OPL setup

### Recommended settings

Consult the [PS2-Home: OPL Recommended Settings](https://www.ps2-home.com/forum/app.php/page/opl_recommended_settings) / [Web archive mirror](http://web.archive.org/web/20230521200731/https://www.ps2-home.com/forum/app.php/page/opl_recommended_settings) thread for a thorough explanation of all of the OPL settings and recommendations.

## Using OPL

### In game reset (IGR)

While playing a game in OPL, `L1+R1+L2+R2+Start+Select` will activate in game reset (IGR) and return to the PS2 memory card menu. However IGR will not work in all games and may cause them to get stuck in a black screen. Consult a compatibility list for any warnings about IGR usage.

!!! warning "IGR path"

    OPL has an option to set a path for the IGR function to boot into instead of the memory card menu. While it is possible to set this path to point to the OPL elf file to return directly to the OPL menu, this may not clear OPL's VMC handshake and could potentially cause difficult to diagnose errors. The PS2-Home guide recommends leaving this at default and re-opening OPL manually to avoid issues.

## OPL compatibility

While OPL with an internal hard drive has a very high game compatibility rate, not all games will be compatible or ready to play with default settings. Before installing game backups, be sure to consult OPL compatibility guides for any warnings or notes. If a game crashes, encounters black screens, or behaves weirdly, try the following steps.

### Compatibility lists

These lists were taken from [jolek's OPL Game Compatibility Lists thread](https://www.psx-place.com/threads/open-ps2-loader-game-compatibility-lists.19037/) with broken or obsolete ones removed.

- [Algol's OPL Game Compatibility List](https://docs.google.com/spreadsheets/d/1K7szQS_9VG8es22eORw3xXTXxp5bZRpHOL6YJDH7S6c/edit?gid=971129131#gid=971129131)
- [OPL-CL](http://sx.sytes.net/oplcl/games.aspx)
- [Compatibility List OPL ZSO](https://docs.google.com/spreadsheets/d/1K7szQS_9VG8es22eORw3xXTXxp5bZRpHOL6YJDH7S6c/edit?gid=971129131#gid=971129131)
- [PS2-Home OPL Game Compatibility List](https://www.ps2-home.com/forum/page/opl-game-compatibility-list) / [Web archive mirror](https://web.archive.org/web/20240612122448/https://www.ps2-home.com/forum/page/opl-game-compatibility-list)

### Compatibility modes

Certain games may not work with OPL's default settings. To fix certain edge cases, OPL allows some of these settings, called **compatibility modes**, to be enabled or disabled per game.

To access these, highlight the game and hit triangle to enter the options screen and select `Game Settings`. After adjusting settings, select `Save Changes` from the options screen. These compatibility modes can toggled in any combination, but some settings are intended to work in conjunction (such as 3 and 6). Consult the compatibility modes guide for more detailed information.

A breakdown of OPL's compatibility modes can be found here: [PS2-Home: OPL Compatibility modes](https://www.ps2-home.com/forum/app.php/page/opl_modes) / [Web archive mirror](http://web.archive.org/web/20230929004713/https://www.ps2-home.com/forum/app.php/page/opl_modes).

### OPL versions

If the compatibility modes don't fix the issue, you may want to try updating your version of OPL or go back to a stable release.

Check the [OPL releases page](https://github.com/ps2homebrew/Open-PS2-Loader/releases) for release options.

Follow [this guide](../install-OPL/) to update OPL.

### Skip FMCB splash screen

Some games will encounter an issue related to the FMCB splash screen, causing them to get stuck on a black screen. To skip the FMCB splash screen, hold R1 while booting up the PS2. Navigate the file browser to boot the OPL elf file directly then select the game.