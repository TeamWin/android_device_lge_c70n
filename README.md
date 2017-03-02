This is a device tree for LG Spirit LTE (codename c70n).

It was created so as to port TWRP to the device. The recovery image can be found at https://forum.xda-developers.com/lg-spirit/development/recovery-unofficial-twrp-lg-spirit-h440n-t3564488

I used Moto G3 (osprey)'s device tree (https://github.com/TeamWin/android_device_motorola_osprey) to port TWRP. I adapted the BoardConfig/fstab and  added dt.img and zImage from stock recovery.

All of this was done under LP. Being on Lolipop was needed to be able to unlock the bootloader which was unlocked by patching the aboot file to trick the phone into thinking that we're booting signed images.
