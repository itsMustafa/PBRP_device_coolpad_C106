# PBRP Tree for Cool1 Dual (C106)
==============

The Cool1 Dual (C106) is a smartphone from Coolpad

Device Configuration for s2
=====================================

Basic   | Spec Sheet
-------:|:-------------------------
CHIPSET | Qualcomm MSM8976 Snapdragon 652
CPU     | Quad-core 1.8 GHz Cortex-A72 & Quad-core 1.4 GHz Cortex-A53
GPU     | Adreno 510
Memory/RAM  | 4 GB
Storage | 32 GB
Battery | 4000 mAh (Non-Removable)
Dimensions | 151.1 x 74.2 x 7.5 mm
Display | 1080 x 1920 pixels 5.5"
Rear Camera  | 13.0 MP + 13.0 MP (Monochrome)
Front Camera | 8.0 MP
Release Date | January 2017

![Cool1 Dual](https://cdn2.gsmarena.com/vv/pics/leeco/leeco-cool1-dual-1.jpg "Cool1 Dual")

To initialize your local repository using the Omnirom trees to build TWRP, use a command like this:

        $ repo init -u git://github.com/PitchBlackRecoveryProject/manifest_pb.git -b android-9.0

Then to sync up:

        $ repo sync

Full Compilation

        $ source build/envsetup.sh

        $ lunch omni_C106-userdebug

        $ make clean

		$ make recoveryimage
