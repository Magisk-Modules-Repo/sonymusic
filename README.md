## Changelog
v1
- Initial Android 5.0+ Release.

v2
- Update Sony Framework Update.
- Template To Newer Magisk Release.

v3
- Initial Android 10 Release.
- Updated Framework
Note*:  Due To Isolated Storage On Android 10 We Have To Type Some Commands In ADB To Enable Legacy Storage Support For This Specific App. Hence The Below Commands Doesn't Influence With Other Apps.
* Enable USB Debugging In Developer Settings
* Launch CMD, Type These Commands Inside Quote:
"adb shell"
"cmd appops set com.sonyericsson.music android:legacy_storage allow"
"am force-stop com.sonyericsson.music"

v4
- Updated Framework
- Hardcoded Storage Strings for scooped storage support
- No Longer Requires ADB Commands
- Updated Template

v5
- Updated Framework
- Remove Prebuilt APK
- Fix Bootloop issues on some devices

## Description
Enables Sony Music Player With Updatable Support From Google Play Store.
*Must Clear PlayStore Data After Installing This Module.*
*Then Install Sony Music App From Playstore*
