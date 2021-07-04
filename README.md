# Magisk on VMOS
Magisk successfully installed on VMOS - but Magisk can't work properly

***Only MagiskSU. This is a experimental feature. If you want modules then don't expect it to work. Modules like MigiskHideProps are not working. So don't expect much.​***

***As of now there is no working way for passing SafetyNet for playing games and apps that use it.***


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

***The installation without boot.img patching. Magisk is installed into VM directly***

VMOS doesn't have `boot.img`, it actually uses the same `/dev` and `/proc` of physical machine (your device).

This is unstable build, so it cannot work properly at all!!

Magisk may not work on your ROM, depend on your fortunateness.

File: [magisk.zip](https://github.com/HuskyDG/Magisk-on-VMOS/releases)

Video: https://youtu.be/rFSNxY3xwo0

Read [How to install modification zip](https://github.com/HuskyDG/VMOSPro_RootXposed_Terminal#how-to-install-a-module) 

<img src="https://i.imgur.com/P2hN7X5.png" />

6. Reboot the virtual machine.

If you want to remove Magisk or switch back to Koush Superuser, just flash mod again!!!
