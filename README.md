CanvasCameraPlugin
============================

This plugin has been updated to support the newest cordova version (~4.0).
It is intended to be used in the iOS version of LastClock (https://lastclock.net)
So some changes might not be for universal usages.

For best performance, the camera is initialized with Low quality at 6 fps.
A new hasNewFrame() function has been added to the js interface which could be used to check if new frame is available.

### To install
```bash
# ~~ from master ~~
cordova plugin add https://github.com/seph14/CanvasCameraPlugin.git && cordova prepare
```

### To remove
```bash
cordova plugin rm com.keith.cordova.plugin.canvascamera
```

## This plugin is forked from

© 2013-2014 Snaphappi, Inc. All rights reserved
