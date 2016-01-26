Build using simple cordova create command just to make a test if running a mobile app also runs the native binary in backend.

In this build app executes the iguana native binary on Android from /data/bin/iguana. This file needed to upload at this location in Android through ADB Shell access, and it must be set to executable.

The test app used cordova plugin: https://www.npmjs.com/package/cordova-plugin-shell-exec

Will be improving on this test app to make it better, and also see if this can work with iOS.