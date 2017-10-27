# Udacity Carnival Starter Project

This project is part of [Udacity](https://www.udacity.com "Udacity - Be in demand")'s [VR Developer Nanodegree](https://www.udacity.com/course/vr-developer-nanodegree--nd017).

## Versions
- Patch 2017.1.0p4
- GVR Unity SDK v1.70.0
- TextMesh Pro v1.0.55.2017.1.0b12

## Caveats

When attempting to push to origin (github) I get the following:

```
remote: Resolving deltas: 100% (962/962), done.
remote: warning: File Udacity Carnival iOS/Libraries/libil2cpp.a is 87.39 MB; this is larger than GitHub's recommended maximum file size of 50.00 MB
remote: error: GH001: Large files detected. You may want to try Git Large File Storage - https://git-lfs.github.com.
remote: error: Trace: 0417abba2ec01a35ef10ca3a8a2a997b
remote: error: See http://git.io/iEPt8g for more information.
remote: error: File Udacity Carnival iOS/Libraries/libiPhone-lib.a is 463.72 MB; this exceeds GitHub's file size limit of 100.00 MB
remote: error: File Udacity Carnival iOS/Pods/GVRSDK/Libraries/libGVRSDK.a is 257.70 MB; this exceeds GitHub's file size limit of 100.00 MB
```

These appear to be library files, which should be easy to get for whomever has experience reviewing. As such I am adding these files to the `.gitignore`.

