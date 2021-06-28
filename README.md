# Magisk on VMOS
Magisk successfully installed on VMOS - but Magisk can't work properly

<img src="https://i.imgur.com/Ny1ekVY.png" />

Hi guy, finally I installed Magisk on VMOS successfully!! Magisk daemon can be running but it can't work properly maybe due to VM limitations.
The newer Magisk (22.0+) app can't detect installed Magisk. 


<img src="https://i.imgur.com/ivTWRnI.jpg" />

But I can grant MagiskSU (make a Superuser request)... Only MagiskSu works

Video: https://youtu.be/eTBd_VtmvqA

NEW!! Magisk Manager v.8.0.0 can detect installed Magisk.

<img src="https://i.imgur.com/YouSCHk.png" />
<img src="https://i.imgur.com/5dDQFRN.png" />

I have made a script to install Magisk as VMOS Tool Terminal modification on VMOS. NOTE that Magisk on VMOS cannot work properly and it is for TEST only!!!

Magisk mount folder: `/sbin/magiskimg`

### How to install Magisk for VMOS Pro

This is unstable build, so it cannot work properly at all!!

Magisk may not work on your ROM, depend on your fortunateness.

File: [magisk.zip](https://github.com/HuskyDG/Magisk-on-VMOS/releases)

Video: https://youtu.be/rFSNxY3xwo0

1. Install VMOS Pro Terminal Tool v1.8+ if it's not installed! Or you can download my Geek ROM with Terminal Tool installed.

2. Download `magisk.zip` and import file to VMOS Pro

3. Extract `magisk.zip` to `magisk` folder

4. Copy `magisk` folder to `/sdcard/toolflash/`

5. Open Terminal app, <del>type `su` (grant root access)</del> then type `tool` to run VMOS Pro Terminal Tool, then type `6` (Enter) and `yes` (Enter) to install module.

<img src="https://i.imgur.com/P2hN7X5.png" />

6. Reboot the virtual machine.

If you want to remove Magisk or switch back to Koush Superuser, just uninstall and reinstall root!!!
