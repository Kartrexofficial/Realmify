# UnBlurify
A module which is meant to remove blur in Realme Devices (Dont Know about Oneplus) This module change the values of System.prop inorder to diable Blur.

# Versions 
There are Two Versions of Blurify 
• UnBlurify Lite - This Removes the Blur on Your System.(No addon)

• UnBlurify - This Removes the Blur and Also adds Animations to Your Realme Launcher 

# Requirments
• Unlocked Bootloader
• Rooted Device
• Module itself

# How to Use
• Flash on Magisk/Kitsune Mask (No idea about KernelSU)
• Always Use Bootloop Protecter Module

# How to use UnBlurify Module on Non Rooted Devices 

Its Quite interesting but You can somehow try to remove blur by changing the Secure Table.Which I won't recommend but You can Give it a try

• Use Settings DataBase Editor App (Available on Play Store)

• Give All Permission Using Adb (Tutorial Is Given in the App itself)

• Copy-Paste the Code Below om the App
````
ro.surface_flinger.supports_background_blur=0
ro.surface_flinger.media_panel_bg_blur=0
ro.oplus.gaussianlevel=1
ro.launcher.blur.appLaunch=0
````
# Compatibility
• Still Not Sure About Everh Device,Pull Request if it didn't work..

