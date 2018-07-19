## unofficial (20180719)~(NDK r10e) 

### Magisk
- Script update, artificially bump version
- Detect ramdisk partition
- Do not early mount on symlinks on half Treble devices
- Prevent build fail when APK is first built without out folder
- Bump Magisk Manager to v5.8.2
- Switch channel and snet APK links
- Huawei hardcodes the slot suffix, don't append the suffix twice
- Merge magiskpolicy into Magisk main repo
- Move magiskpolicy sources to native/jni/magiskpolicy
- Remove magiskpolicy as submodule
- Merge MagiskSU into Magisk main repo
- Remove MagiskSU as submodule
- Move MagiskSU sources to native/jni/su
- Merge Magisk Manager into Magisk main repo
- Remove Magisk Manager as submodule
- Move Magisk Manager files into subfolder
- Prevent crashing on broken module.prop
- Log fatal errors in debug mode only
- Dump binaries to header at build, not at request
- Read fstab from device tree
- Use xwrap functions
- Support deodexed ROM on Oreo
- SIGPIPE is handled in main daemon
- Several adjustments
- Fix force denying on exit
