# SailfishOS 3.2.1.20 for Redmi 4X (Santoni)

## What is SailfishOS?
> SailfishOS is a general purpose Linux distribution used commonly as a mobile operating system combining the Linux kernel for a particular hardware platform, the open-source Mer core stack of middleware, a proprietary UI contributed by Jolla or an open source UI, and other third-party components.

## Disclaimer:
```
/*
 * Your warranty is now void.
 *
 * I am not responsible for bricked devices, dead SD cards,
 * thermonuclear war, or you getting fired because the alarm app failed. Please
 * do some research if you have any concerns about features included in this ROM
 * before flashing it! YOU are choosing to make these modifications, and if
 * you point the finger at me for messing up your device, I will laugh at you.
 */
 ```
 
 ## What's not working?
 - Fingerprint
 - Android APK **THIS IS NOT ANDROID, THAT MEANS THERE IS NO WAY TO RUN APK**
 - Bluetooth
 - FM Radio
 - GPS
 Maybe more stuff.
 
 ## Why is the Jolla Store empty?
 - Since our device is not registered by Jolla yet, use **Storeman** to get apps.
 
 ## Installation
1. Download [LOS 15.1](https://github.com/freebytego/santonifish/releases)
2. Download [SailfishOS](https://github.com/freebytego/santonifish/releases)
3. **Use official TWRP Recovery**
4. Reboot to TWRP
5. Make sure /data and /cache are in **ext4** format.
6. Wipe Dalvik, Data, Cache, System, Vendor
7. Copy LineageOS and Sailfish ZIP to phone
8. Flash LOS 15.1
9. Flash SailfishOS
10. Reboot!


## Source code
SailfishOS UI and system apps are proprietary.

Droid configurations droid hal, etc check [here](https://github.com/freebytego)

## Special thanks
- [Danct12](https://github.com/danct12) and his Discord
- Sailfish-Porting Telegram
