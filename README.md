# What is rOS and it's meaning?
rOS, or, longer, randomOS, is a mobile OS based off AOSP (read: Android Open Source Project) or LineageOS.

# What is the goal of rOS?
There isn't any goal, it's just once again a mobile OS that exists for absolutely no reason.

# What is the difference between other mobile OS like LineageOS, crDroid, Pixel OS etc.?
For example, there is a difference between features and booting.

# How to install it?

```I AM NOT RESPONSIBLE FOR ANY BRICKED OR BOOTLOOPED DEVICE. YOUR WARRANTY IS VOIDED. IF YOU WILL BLAME ME FOR BRICKING, BOOTLOOPING OR ANY ERROR YOUR DEVICE GOT INTO, I WILL LAUGH. I AM NOT FORCING YOU TO USE, MAINLY DRIVE OR FLASH THIS OS.```

BACK UP  YOUR DATA INTO A CLOUD.
1. Unlock the bootloader (Tap 7 times on "Build Number", go to Developer Options and there press "OEM Unlock", but you should log out of any accounts to prevent EPF... EFP... idk) and boot into Download Mode, Fastboot or whatever using a specific buttons combination.
2. Get a TWRP SPECIALLY FOR YOUR DEVICE. Flashing TWRP for another device or even the same device with a mismatched model code (like mistaking SM-N960F with another Note 9 version build) can or may result in a bootloop, a brick etc.
3. Get rOS for your device. Flashing rOS for another device or even the same device with a mismatched model code (like mistaking SM-N960F with another Note 9 version build) can or may result in a bootloop, a brick etc.
4. Flash TWRP using Fastboot, Odin or whatever thing your phone has.
5. Boot into TWRP.
6. Flash rOS
   ADB: Go into Advanced -> ADB Sideload -> choose "Wipe Cache or ART/Dalvik cache" -> Next. Connect your phone to a PC via a USB-A to whatever port your phone has, open terminal and type "adb sideload filename.zip" and wait. Note for Windows devices: You need to download your manufacturer's driver for ADB to be able to see your phone, use "adb devices" to check on that.
   TWRP: OR you can use TWRP flasher. Go to Flash -> *locate the file you got* -> flash. In order to get the file on your phone use "adb push /path/to/your/file.zip /path/where/to/copy" or for Windows "adb push diskletter\path\to\your\file.zip /path/where/to/copy".
7. (If you want Gservices and Gapps) Find a proper Gapps for your Android version (example if you have rOS 1.0 then Android 16 etc.), architecture and the amount of Gservices and Gapps you want. I personally recommend MindTheGapps, but you don't need to install only it, you can use whatever Gapps you want!
8. Boot into the system.
9. random your phone! (haha you get it random like random in the name)
If you got into trouble while using this guide, i recommend you to find more guides and research on XDA or wherever.

# If i got a soft bootloop, what do i do?
In a soft bootloop you can actually reflash, for this go to Fastboot, Download Mode or whatever and use the guide up there.

# If i got a hard bootloop, what do i do?
In a hard bootloop i can't actually help you, try to find guides on YouTube, XDA Forum, or go to a service and pray you have warranty (you don't, you unlocked the bootloader)

# Which apps are included in this ROM?
Apps here is AOSP apps, which can look like Google apps ripoff, but it is made by Google.

# How do i install Gapps?
You need to install Gapps (Google Apps) after flashing rOS. If you will reboot after flashing rOS, flashing Gapps may fail, so, if you want Gapps but already got the ROM on your phone, go to TWRP, then "Wipe", "Advanced Wipe", wipe Internal Storage, Data (If you don't need your photos or apps saved), System, and both ART/Dalvik Cache and Cache. Then, go back, "Wipe data" and type "yes", press "Wipe".
Go to Flash, flash rOS, DO NOT reboot into System, flash Gapps. Now reboot to system and use rOS with Gapps.
