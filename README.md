## !! Coop bhaptics still has issues, currently being worked on !!

# IntoTheRadius2 bHaptics and ForceTube mod

<img src="https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/2307350/header.jpg">

# Description

Into The Radius 2 bHaptics and Provolver/ForceTube mod. Vest and Arms are supported.</br></br>
[https://store.steampowered.com/app/2307350/Into_the_Radius_2/](https://store.steampowered.com/app/2307350/Into_the_Radius_2/)

☕ If you wanna show some support you can buy me a coffee : https://www.buymeacoffee.com/astienth4

# <b>Installation</b></br>

1) Download the zip file from [https://github.com/Astienth/IntoTheRadius2_bHaptics_ForceTube/releases/download/0.0.1/Into_the_Radius2_bHaptics_Provolver_0.13.15.zip](https://github.com/Astienth/IntoTheRadius2_bHaptics_ForceTube/releases/download/0.0.1/Into_the_Radius2_bHaptics_Provolver_0.13.15.zip)</br>
2) Extract its content into the game root folder, the folder containing the IntoTheRadius2.exe.</br>
3) Launch bhaptic player and turn your devices on if you use bHaptics. Turn your protube device on if you use protube devices (READ THE PROTUBE SECTION FOR CONFIG)</br>
4) Launch the game like you usually launch it

If you already installed a previous version of the mod, you can just overwrite everything and you don't need the previous method to launch the mod. It is now automatic !

# Protube configuration:
if you want to use two protube devices, one in EACH hand, then you need the "dualwield" config: move the file "dualwield.cfg" from "IntoTheRadius2\Binaries\Win64\Mods\Bhaptics" to "IntoTheRadius2\Binaries\Win64\Mods\Bhaptics\Scripts"
Protube devices are limited to two devices. First recognized device is assigned to pistol1 and second to pistol2.
You can have those configurations :
- one protube and one provolver => single wield, same action is sent to both devices. The file "dualwield.cfg" MUST NOT BE in Mods\Bhaptics\Scripts, leave it anywhere else.
- two provolvers => dualwield, one in each hand, you NEED the dualwield.cfg file in the correct folder (Mods\Bhaptics\Scripts). Right hand is pistol1, left hand is pistol2
- only one device => single wield, the file "dualwield.cfg" MUST NOT BE in Mods\Bhaptics\Scripts, leave it anywhere else. Device will be registered as pistol1 and will receive any weapon shot fro many hand (this means that if you have one weapon in each hand and use both, they both will trigger your single protube device. There is no other way to determine which weapon or which hand to use with a single device).

# <b>Limitations</b>
This is a basic mod for the time being, the game is in early access and is likely to break with each new update.

# License:
UE4SS is used to hook into the game. UE4SS is under MIT licence provided.
Any file not related to UE4SS is not under this MIT license
