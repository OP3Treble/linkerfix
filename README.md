# linkerfix
This repo contains a linker (32-bit) binary with shim libs support compiled in.

This linker supports unofficial OP3Treble Project:

```Makefile
TARGET_LD_SHIM_LIBS := \
    /vendor/lib/hw/camera.msm8996.so|libcamera_shim.so
```

Reference: https://review.lineageos.org/c/LineageOS/android_bionic/+/223065/6
           https://github.com/phhusson/treble_experimentations/issues/165
