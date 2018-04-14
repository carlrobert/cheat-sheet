# cheat-sheet

## Android adb
* SELinux `setenforce` and `getenforce`: http://sgeos.github.io/android/selinux/2016/05/22/setting-the-android-selinux-mode.html
* `adb shell am force-stop <package name>` Alternatively, use `kill` instead of `force-stop` 

## Gradle
Include parts from a different project or git:
```
include ':audio-device'
project(':audio-device').projectDir = new File('../oboe/samples/audio-device')
```
Note the two different file path syntaxes :)
