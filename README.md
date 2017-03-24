# ClassicWB ADVSP Package

## Description

ClassicWB ADVSP Package contains ClassicWB ADVSP v28 created by Bloodwych from EAB.

ClassicWB ADVSP is a feature rich Workbench enhancement by Bloodwych targeted A1200 with accelerator, memory expansion using Multisync / Interlaced 640x512 display.

With permission from Bloodwych it's been converted to a package for HstWB Installer.

Original version of ClassicWB ADVSP can be downloaded from http://classicwb.abime.net/.

## Installation

Download latest release [here](../../releases) and copy it to HstWB Installer "packages" directory, which typically is "c:\Program Files (x86)\HstWB Installer\Packages".

## Modifications

ClassicWB is installed from a zip file containing all files from ClassicWB System.hdf.

The install script for HstWB Installer is based on S/Startup-Sequence from ClassicWB System.hdf with following changes:

- Removed Workbench installation.
- Paths has been changed: SYS: to SYSTEMDIR:, C: to SYSTEMDIR:C/, L: to SYSTEMDIR:L/.
- Modified versions of Temp enable and disable option scripts with changed paths.
- Removed all "press enter to continue" expect last one used after installation complete message is shown.
- Removed and reduced waits.
- Adjusted text spacing.