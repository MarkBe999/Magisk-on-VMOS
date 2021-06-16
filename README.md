# Magisk on VMOS
Magisk successfully installed on VMOS - but Magisk can't work properly

<img src="https://i.imgur.com/Ny1ekVY.png" />

Hi guy, finally I installed Magisk on VMOS successfully!! Magisk daemon can be running but it can't work properly maybe due to VM limitations.
Magisk app can't detect installed Magisk. 


<img src="https://i.imgur.com/ivTWRnI.jpg" />

But I can grant MagiskSU (make a Superuser request)...

Video: https://youtu.be/eTBd_VtmvqA

Remember: All "Magisk on VMOS" videos uploaded to YouTube are fake.  They just install the Magisk manager app (like any app you install with "file.apk") on the VMOS.

NEW!! Magisk Manager v.8.0.0 can detect installed Magisk.

<img src="https://i.imgur.com/YouSCHk.png" />
<img src="https://i.imgur.com/5dDQFRN.png" />

I have made a script to install Magisk as VMOS Tool Terminal modification on VMOS. NOTE that Magisk on VMOS cannot work properly and it is for TEST only!!!



### How to install Magisk for VMOS Pro

File: [magisk-vmos.zip](https://github.com/HuskyDG/Magisk-on-VMOS/releases)

1. Install VMOS Pro Terminal Tool v1.8+ if it's not installed! Or you can download my Geek ROM with Terminal Tool installed.

2. Download `magisk-vmos.zip` and import file to VMOS Pro

3. Extract `magisk-vmos.zip` to `magisk-vmos` folder

4. Copy `magisk-vmos` folder to `/sdcard/toolflash/`

5. Open Terminal app, type `daemonsu` (grant root access) then type `tool` to run VMOS Pro Terminal Tool, then type `6` (Enter) and `yes` (Enter) to install module.

<img src="https://i.imgur.com/P2hN7X5.png" />

6. Reboot the virtual machine.
