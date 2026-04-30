# SM-T590-Samsung-Experience-9-package-for-downgrading-from-U3-binary
A package to downgrade the Galaxy Tab A (2018, 10.5), a.k.a. SM-T590 from One UI 1 or 2 to Samsung experience, even though one UI uses the newer U3 binary

### All glory to God, who created everything, while he himself is uncreated ###

# General Info
These images use the EUR region's CSC, and there are a few bugs from altering the stock rom, such as the battery tab appearing twice in settings, and a notification about unauthorized actions on every startup. HOWEVER, ignoring these, the device should work totally fine, and even propertiary samsung apps, such as the galaxy store, secure folder, and daily board.

# IMPORTANT
Keep in mind that to install this, you will need an unlocked bootloader, the TWRP recovery made by @UDPSendToFailed (https://github.com/UDPSendToFailed/twrp_device_samsung_gta2xlwifi/), and a windows/linux PC to use Odin on.

# Installation instructions
 1) Unlock the bootloader
 2) download twrp and Odin patched by SamFw
 3) put the device in download mode, by using the recovery and selecting reboot to bootloader
 4) Uncheck "Auto Reboot" from Odin's Options
 5) put the TWRP recovery in the AP slot and flash your tablet
 6) Immidiately boot into TWRP, or else it will be overwritten
 7) In TWRP, format data, wipe all the partitions using advanced wipe, and reboot into recovery
 8) Chose install from TWRP's home screen, click "Install Image", and then install every image to it's corrresponding partition
 9) reboot into system
### Note, the first boot will take A LOT of time, don't panic since it is not bootlooping ###

# Notes
 - Personally, I had downgraded my tablet to the first U3 build of android 9 before flashing, but I believe that flashing 8.1 on a fully updated device will as well work.
 - on every boot you will se a yellow text saying "set warranty bit: kernel" on the bootloader. Don't worry, this is perfectly normal and it just indicates that you are not running an official signed image.
 - I believe flashing the recovery is totally optional, and bypassing it may be useful in case you want to root your tablet afterwards. However, I have not tested this myself and I can not gurantee anything.
 - This will NOT change the baseband version, and will NOT let you flash any U2 image using odin. It is just an altered version of the stock rom with the U2 indicator and some other stuff removed/altered

### And just to be typical, let me include this: ###

* Your warranty is now void.
(But I mean it's probably already void at this point... bleh.)

* I am not responsible for bricked devices, dead SD cards,
* thermonuclear war, or you getting fired because the alarm app failed.
* YOU are choosing to make these modifications and if
* YOU point the finger at me for messing up your device,
* I will laugh at you.
