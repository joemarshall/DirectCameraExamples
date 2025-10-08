# Direct Camera Android for Unreal Example Project


## The plugin

DirectCamera Android is a plugin for Unreal Engine which gives full, GPU accelerated access to the Android Camera, including multi-camera support, changing camera settings such as exposure, live capture to texture, plus JPG and raw file writing etc.

For more info, check out (https://joemarshall.github.io/directvideo/directcamera_unreal.html)

## Building

You need to have purchased and installed the plugin to your Unreal installation first.

Build using the make_releases.py script.

```
python .\make_releases.py build android
```

This assumes you have unreal under `c:\\epic`. If it is somewhere else, you need to add the `-ue-path <path>` argument to the script.

You can also build a Quest passthrough camera example by calling 
```
python .\make_releases.py build quest
```

For help on the build script, run 
```
python make_releases.py build -h
```

For plugin documentation go to (http://joemarshall.github.io/directvideo).