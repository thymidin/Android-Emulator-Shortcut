# Android-Emulator-Shortcut

Here is a simple AppleScript app to launch AVD without Android Studio. 
You will need to follow this simple guide to make an app from this script. 

## Prerequisites 

Be sure Android Studio is installed on macOS. Create a virtual device on AVD to be able to launch it.

## Retreive the name of your virtual device

In terminal type :

`cd ~/Library/Android/Sdk/emulator && ./emulator -list-avds`

You now should have your virtual device name.

## Modify your script

Open Android Emulator.scpt with AppleScript and replace "Pixel_3a_API_33_x86_64" with your virtual device name.
Save it and export it (Files -> Export...) by selecting "Application". You now have an app you can put in /Applications and in the Dock to launch AVD. 
