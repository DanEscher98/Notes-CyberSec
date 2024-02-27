# DEVLOG

- Template `Cisco IOU L2 15.2d`
    [Setup IOU](https://docs.gns3.com/docs/emulators/non-native-iou-for-windows-and-osx/)
    [Fix `IOU Licence Error`](https://gns3.com/community/featured/iou-license-error-3)
- Template `Cisco IOSvL2 15.2.4055`
    After succesfully installing in local Linux with QEMU, found `CPU exception
    occurred: Overflow(4) (SIGSTOP, 4, 0x4)` at boot. Solved by adding
    `-machine pc-q35-4.2` to `Switch>Configure>Advanced>Options`
