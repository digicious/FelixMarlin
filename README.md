================================================
FelixPrinters fork of Marlin 3D Printer Firmware
================================================
This fork was created in order to provide an easy-to-use setup of the Marlin firmware
that is preconfigured to work with the FelixPrinters 2.0/3.0 electronics, but which is
kept more up to date with ongoing Marlin feature/bugfix development than the firmware available
at the official FelixPrinters web site.

The mainstream Marlin codebase is undergoing some significant restructuring and bug fixing at the moment.
I am making periodic merges of these changes and testing with the Felix-specific settings, and publishing
to this fork when they appear to be reasonably stable.  Build breaks are fairly common at the moment, so
I am not publishing my local merges unless I'm certain that this build is in a working state - it should
be fairly safe to continue to use the FelixMarlin fork.

Marlin mainstream README follows:
# Marlin 3D Printer Firmware
<img align="right" src="Documentation/Logo/Marlin%20Logo%20GitHub.png" />

  * [Configuration & Compilation](/Documentation/Compilation.md)
  * Supported
    * [Features](/Documentation/Features.md)
    * [Hardware](/Documentation/Hardware.md)
    * [GCodes](/Documentation/GCodes.md)
  * Notes
    * [Auto Bed Leveling](/Documentation/BedLeveling.md)
    * [Filament Sensor](/Documentation/FilamentSensor.md)
    * [Ramps Servo Power](/Documentation/RampsServoPower.md)

##### [RepRap.org Wiki Page](http://reprap.org/wiki/Marlin)

## Quick Information

This is a firmware for reprap single-processor electronics setups.
It also works on the Ultimaker PCB. It supports printing from SD card+Folders, and look-ahead trajectory planning.
This firmware is a mashup between [Sprinter](https://github.com/kliment/Sprinter), [grbl](https://github.com/simen/grbl) and many original parts.

## Current Status: Bug Fixing

The Marlin development is currently revived. There's a long list of reported issues and pull requests, which we are working on currently.
We are actively looking for testers. So please try the current development version and report new issues and feedback.

[![Coverity Scan Build Status](https://scan.coverity.com/projects/2224/badge.svg)](https://scan.coverity.com/projects/2224)
[![Travis Build Status](https://travis-ci.org/MarlinFirmware/Marlin.svg)](https://travis-ci.org/MarlinFirmware/Marlin)

What bugs are we working on: [Bug Fixing Round 2](https://github.com/MarlinFirmware/Marlin/milestones/Bug%20Fixing%20Round%202)

## Contact

__IRC:__ #marlin-firmware @freenode ([WebChat Client](https://webchat.freenode.net/?channels=marlin-firmware), [Archive](http://energymonitor-dk.dns4e.net/marlin-firmware-log/))

__Mailing List:__ marlin@lists.0l.de ([Subscribe](http://lists.0l.de/mailman/listinfo/marlin), [Archive](http://lists.0l.de/pipermail/marlin/))

## Credits

The current Marlin dev team consists of:

 - Erik van der Zalm ([@ErikZalm](https://github.com/ErikZalm))
 - [@daid](https://github.com/daid)
 
Sprinters lead developers are Kliment and caru.
Grbls lead developer is Simen Svale Skogsrud.
Sonney Jeon (Chamnit) improved some parts of grbl
A fork by bkubicek for the Ultimaker was merged.

More features have been added by:
  - Lampmaker,
  - Bradley Feldman,
  - and others...

## Licence

Marlin is published unde the [GPL license](/Documentation/COPYING.md) because I believe in open development.
Please do not use this code in products (3D printers, CNC etc) that are closed source or are crippled by a patent.

[![Flattr this git repo](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=ErikZalm&url=https://github.com/MarlinFirmware/Marlin&title=Marlin&language=&tags=github&category=software)
