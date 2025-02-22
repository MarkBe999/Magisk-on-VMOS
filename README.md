# Magisk on VMOS
Magisk successfully installed on VMOS - but Magisk can't work properly

***Only MagiskSU. MagiskHide cannot hide root and Magisk module cannot work. This is a experimental feature. If you want modules then don't expect it to work. Modules like MigiskHideProps are not working. So don't expect much.​***

***As of now there is no working way for passing SafetyNet for playing games and apps that use it.***

**No benefit of replacing old root with Magisk**

<img src="https://i.imgur.com/Ny1ekVY.png" />

Hi guy, finally I installed Magisk on VMOS successfully!! Magisk daemon can be running but it can't work properly maybe due to VM limitations.
The newer Magisk (22.0+) app can't detect installed Magisk. 

## Why doesn't Magisk work properly in VMOS?

VMOS is system-on-proot, actually not a emulator, virtual machine

<img src="https://i.imgur.com/ivTWRnI.jpg" />

But I can grant MagiskSU (make a Superuser request)... But when I press **GRANT** button, Terminal doesn't show anything, I cannot type and call any command after that!

Video: https://youtu.be/eTBd_VtmvqA

NEW!! Magisk Manager v.8.0.0 can detect installed Magisk.

<img src="https://i.imgur.com/YouSCHk.png" />
<img src="https://i.imgur.com/5dDQFRN.png" />

I have made a script to install Magisk as VMOS Tool Terminal modification on VMOS. NOTE that Magisk on VMOS cannot work properly and it is for TEST only!!!

Magisk fake boot: `/.boot/magisk`

### How to install Magisk for VMOS Pro

***The installation without boot.img patching. Magisk is installed into VM directly***

File: [magisk.zip](https://github.com/HuskyDG/Magisk-on-VMOS/releases)

Read [How to install modification zip](https://github.com/HuskyDG/VMOSPro_RootXposed_Terminal#how-to-install-a-module) 

<img src="https://i.imgur.com/P2hN7X5.png" />

If you want to remove Magisk or switch back to Koush Superuser, just flash mod again!!!
