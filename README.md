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

## Quantum Computing Study Resources
* Mike and Ike: summary + book link
* IBM Q Experience: https://quantumexperience.ng.bluemix.net/qx/editor
* Brilliant app: https://brilliant.org/ Learn Maths + notation
* IBM video, five levels of sophistication: https://www.youtube.com/watch?v=OWJCfOvochA&index=35&list=LLeuRk0d3oAtrgiIkqVyqW0w&t=0s
* Microsoft talk: https://www.youtube.com/watch?v=F_Riqjdh2oM&index=33&list=LLeuRk0d3oAtrgiIkqVyqW0w&t=0s
* Microsoft Quantum Development Kit
* Lund University Quantum Computing Course
