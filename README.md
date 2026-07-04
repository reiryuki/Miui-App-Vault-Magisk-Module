# Miui App Vault Magisk Module

## DISCLAIMER
- Miui apps are owned by Xiaomi™.
- The MIT license specified here is for the Magisk Module only, not for Miui apps.

## Descriptions
- App Vault by Xiaomi Inc. ported and integrated as a Magisk Module for all supported and rooted devices with Magisk
- Adds App Vault feature in Miui Home (com.miui.personalassistant if in normal/CN mode of Miui Core, com.mi.android.globalminusscreen if in global mode of Miui Core)
- Adds widgets feature in Miui Security

## Sources
https://apkmirror.com com.miui.personalassistant & com.mi.android.globalminusscreen by Xiaomi Inc.

## Changelog

v0.6
- Prepare /storage/emulated/"$USR"/Android/data/$PKG/files

v0.5
- Fix SystemUI visibility while changing between dark and light theme immediately
- Add Action button to clear apps caches
- Fix architecture detection in some weird ROMs
- Fix bug in uninstall.sh

v0.4
- Android Emulator support

v0.3
- Fix wrong declaration of android.permission.PACKAGE_USAGE_STATS in GlobalMinusScreen.apk

v0.2
- Fix conflict with modules_update while installing via recovery if Magisk installed
- Fix MagiskHide & SUList
- Add missing QUERY_ALL_PACKAGES permission and largeHeap="false" in global mode (com.mi.android.globalminusscreen)
- Fix crash in Android 12 and up by setting FLAG_IMMUTABLE at getBroadcast
- Fix status bar visibility in dark mode

v0.1
- Initial release

## Screenshots
- https://t.me/androidryukimodsdiscussions/226355
- https://t.me/ryukinotes/7

## Requirements
- NOT in Miui ROM
- Android 5 (SDK 21) and up
- Magisk or Kitsune Mask or KernelSU or Apatch installed
- Miui Core Magisk Module installed

## Installation Guide & Download Link
- If you are using KernelSU, you need to disable Unmount Modules by Default in KernelSU app settings and install https://github.com/KernelSU-Modules-Repo/meta-overlayfs or https://github.com/KernelSU-Modules-Repo/magic_mount_rs or https://github.com/KernelSU-Modules-Repo/hybrid_mount or https://github.com/maxsteeel/nomount first depending on ROM compatibility
- Install Miui Core Magisk Module first: https://github.com/reiryuki/Miui-Core-Magisk-Module
- Install Miui Home Magisk Module and/or Miui Security Magisk Module
- Install this module https://devuploads.com/7efly89v2rk7 via Magisk app or Kitsune Mask app or KernelSU app or Apatch app or Recovery if Magisk or Kitsune Mask installed
- Reboot
- If you are using KernelSU, you need to allow superuser list manually all package name listed in package.txt (and your home launcher app also) (enable show system apps) and reboot afterwards
- If you are using SUList, you need to allow list manually your home launcher app (enable show system apps) and reboot afterwards
- Go to app info of App vault and allow it's network access

## Optionals
- https://t.me/ryukinotes/42
- Global: https://t.me/ryukinotes/35

## Troubleshootings
- https://t.me/ryukinotes/19
- Global: https://t.me/ryukinotes/34

## Support & Bug Report
- https://t.me/ryukinotes/54
- If you don't do above, issues will be closed immediately

## Credits and Contributors
- https://t.me/androidryukimodsdiscussions
- You can contribute ideas about this Magisk Module here: https://t.me/androidappsportdevelopment

## Sponsors
https://t.me/ryukinotes/25


