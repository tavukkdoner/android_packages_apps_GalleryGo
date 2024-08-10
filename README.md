# Add in local manifest

```
 <remote  name="tavukkdoner"
           fetch="https://github.com/tavukkdoner"
           revision="lineage-21" />

<project path="packages/apps/GalleryGo" name="android_packages_apps_GalleryGo" remote="tavukkdoner" revision="inherit" />
```

# Add following in device.mk

```
# Google Gallery Go
$(call inherit-product, packages/apps/GalleryGo/config.mk)
```

Source of APK: https://apkpure.com/gallery/com.google.android.apps.photosgo 1.9.1.597540607 version

https://www.virustotal.com/gui/file/0fd4930e9d9dfa8b1ce5b84aa5443ad42f3f8e800a799bd7b64b8268a5ef431a
