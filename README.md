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

## Google firmware
[Nexus and Pixel firmware labels](https://developers.google.com/android/images) and the [mapping between builds and tags](https://source.android.com/setup/start/build-numbers)
