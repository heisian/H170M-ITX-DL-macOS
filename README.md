# H170M-ITX-DL-macOS
This is a working EFI/Clover configuration complete with `config.plist` and applicable kexts for macOS 10.12.6.

## System Specs
* ASRock H170M-ITX/DL
* Intel i3-6100 3.7GHz
* Crucial Ballistix Sport LT 8GB
* Samsung 850 EVO 250GB mSATA SSD
* MSI GeForce GT 710
* Antec ISK 310-150 Mini ITX Desktop Case w/ 150W PSU
* Noctua NH-L9i Low-profile CPU Cooler

https://pcpartpicker.com/user/heisian/saved/fbsvVn

## Installation Guide
http://www.insanelymac.com/forum/topic/312085-guide-macos-sierra-1012x-on-asrock-h170m-itxac/page-18

## Post-install Actions
* Make sure to use `uuidgen` to update the `SMBIOS` `SmUUID` for iMessage (and the `config.plist` to be valid) to work.
* Activate NVIDIA HDMI Audio: https://github.com/toleda/audio_CloverHDMI/raw/master/audio_cloverHDMI-130.command.zip
* I did NOT install NVIDIA web drivers. Installing the driver caused icon artifacts, and so it was uninstalled and everything performs fine.
