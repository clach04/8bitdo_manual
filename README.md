# 8bitdo manual

The missing manual, documentation for 8bitdo gamepad controllers (initial focus the NES30/N30/F30).

Latest version available from https://clach04.github.io/8bitdo_manual/

So you have a 
http://www.8bitdo.com/retro-receiver-nes-classic what's next?

First thing is to flash the latest firmware.


The NES30 was renamed after release to the N30.
Same firmware/controls for N30/F30 and SN30/SF30.
Even though the N30/F30 is discontinued, there are recent firmware updates.

## Firmware

There is firmware for the game controller.
There is also firmware for retro receivers for use on original consoles.

### Retro receiver firmware

No recommendations at this time, see https://github.com/ClusterM/hakchi2/issues/257
And consider gamepad controller firmware 2.70 which allows to remap Turbo (L/R/X/Y) buttons via RemapTool. alternative is to start in Switch mode with latest firmware.

### Controller firmware

  * current/new as of May 2019 latest is 4.20 - http://download.8bitdo.com/Firmware/Controller/N30+F30/
  * legacy 3.0 - http://download.8bitdo.com/Firmware/Controller/N30+F30/
  * Original 2.x - from http://download.8bitdo.com/Firmware/GamePad/

For updating firmware under Linux, see https://github.com/hughsie/8bitdo-firmware

For Microsoft Windows and Apple MacOs see 8bitdo support and downloads.

Firmware change logs:

  * https://web.archive.org/web/20170520112357/http://www.8bitdo.com/snes30/firmware.html


#### Current firmware 4.x

recommended, most instructions and documentation online is for version 4.0 and later.

#### Legacy 3.0

Last version to support iOS and keyboard emulation mode.

#### Original 2.x

Version 2.70 appears to be the last version to support button remapping, via the Remap tool (provided in the same zip the 2.70 firmware is in).
If using GamePad with a retro receiver (for example, with original NES console consider this version).

## Connecting gamepad

### USB cable

With new firmware, can plug in USB cable and it will just work. Older firmware needs to have USB mode enabled.

### Bluetooth pairing

If prompted for a PIN code, use 0000. Note this may only be for certain firmware versions



## Other resources

  * http://support.8bitdo.com/
      * http://download.8bitdo.com/Manual/Controller/N30+F30/ version 4 and legacy documents
      * http://download.8bitdo.com/Manual/Receiver/nes_classic/
      * https://apps.fcc.gov/oetcf/eas/reports/ViewExhibitReport.cfm?mode=Exhibits&RequestTimeout=500&calledFromFrame=N&application_id=7m%2FRN9p%2Fv8MKEPZXeG4UyQ%3D%3D&fcc_id=2AH7N-SNES30 fcc application for SNES30, documentation here is more detailed (not pretty v4.x firmware), translation appears to be from third party.
  * https://github.com/RetroPie/RetroPie-Setup/wiki/8Bitdo-Controller
  * https://github.com/recalbox/recalbox-os/wiki/8bitdo-on-recalbox-(EN) note instructions are for 2.x firmware
  * udev rules https://github.com/paalfe/mixedcontent/blob/master/udev_rules.d/99-8bitdo-bluetooth-controllers.rules

