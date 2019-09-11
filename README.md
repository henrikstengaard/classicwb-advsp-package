# ClassicWB ADVSP Package

ClassicWB ADVSP is a feature rich Workbench enhancement by Bloodwych targeted A1200 with accelerator, memory expansion using Multisync / Interlaced 640x512 display.

## Description

ClassicWB ADVSP Package contains ClassicWB ADVSP v28 created by Bloodwych from EAB.

With permission from Bloodwych it has been converted to a package for HstWB Installer.

Original version of ClassicWB ADVSP can be downloaded from http://classicwb.abime.net/.

## Requirements

ClassicWB ADVSP package can be installed on any Amiga with Amiga OS 3.1 or 3.1.4 and about 117MB free space on a harddrive for installation.

## Installation

Download latest release from https://github.com/henrikstengaard/classicwb-advsp-package/releases and copy it to HstWB Installer "packages" directory, which typically is "c:\Program Files (x86)\HstWB Installer\Packages".

Installation through HstWB Installer will install and configure ClassicWB ADVSP package using defined assigns.
During installation dialogs are presented to customize ClassicWB installation.

## Assigns

Installation of ClassicWB ADVSP package requires and uses following assign and default value:

- SYSTEMDIR: = DH0:

ClassicWB ADVSP files will be installed and configured in SYSTEMDIR: assign, which must be set to harddrive containing Workbench.

## Modifications

ClassicWB is installed from a zip file containing all files from ClassicWB System.hdf.

The install script for HstWB Installer is based on S/Startup-Sequence from ClassicWB System.hdf with following changes:

- Removed Workbench installation.
- Paths has been changed: SYS: to SYSTEMDIR:, C: to SYSTEMDIR:C/, L: to SYSTEMDIR:L/.
- Modified versions of Temp enable and disable option scripts with changed paths.
- Removed all "press enter to continue" expect last one used after installation complete message is shown.
- Removed and reduced waits.
- Adjusted text spacing.
- Added support for Amiga OS 3.1.4:
  - Reinstalled MUI to fix Scalos prefs and iGame.
  - Disabled PatchRAM, StackAttack, FBlit and FText.
  - Patched Scalos title to 3.1.4 for no theme, Oldicons, Retro and ReGen themes.
  - Disable Scalos option to fix NewIcons shown garbled or distorted, which will add following as a replacement for Scalos:
    - Full Palette for better colors in icons.
    - Tools Daemon for added options in Workbench top menu.
    - Magic Menu for right click menu in Wokrbench.
  - Added LoadModule ROMUPDATE to support Kickstart 3.1 being patched to 3.1.4.
  - Added version checking of DEVS:scsi.device, so it only will be loaded if scsi.device in memory/resident is less than v43.45.
  - Added install patch Amiga OS 3.1.4.1, if Amiga OS 3.1.4.1 update is installed. 

## Screenshots

Screenshots of ClassicWB ADVSP from http://classicwb.abime.net/classicweb/advsppics.htm.

![ClassicWB ADVSP 3.1.4 1](screenshots/classicwb_advsp_3.1.4_1.png?raw=true)

![ClassicWB ADVSP 3.1.4 2](screenshots/classicwb_advsp_3.1.4_2.png?raw=true)

![ClassicWB ADVSP 1](screenshots/classicwb_advsp1.png?raw=true)

![ClassicWB ADVSP 2](screenshots/classicwb_advsp2.png?raw=true)

![ClassicWB ADVSP 3](screenshots/classicwb_advsp3.png?raw=true)

![ClassicWB ADVSP 4](screenshots/classicwb_advsp4.png?raw=true)

![ClassicWB ADVSP 5](screenshots/classicwb_advsp5.png?raw=true)

![ClassicWB ADVSP 6](screenshots/classicwb_advsp6.png?raw=true)

![ClassicWB ADVSP 7](screenshots/classicwb_advsp7.png?raw=true)

![ClassicWB ADVSP 8](screenshots/classicwb_advsp8.png?raw=true)