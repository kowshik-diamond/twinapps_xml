Edit the xml with your required app package names.

Download xml to your PC/laptop .
push the xml to your phone via adb " adb push twinapps.xml /sdcard/ "
and give required permission to xml to work " adb shell am startservice -a "asus.intent.action.TWINAPPS_CDN_FILE_UPDATE" -d "file:///sdcard/twinapps.xml" --ei "ACTION" 1 com.asus.twinapps/.TwinAppsService "
