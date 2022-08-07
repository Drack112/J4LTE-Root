# SM-J400M LTE - Root

I published this repository in order to save my files and tools to ROOT my Samsung Galaxy J4 ( SM-J400M lte ) device.

If you want, feel free to use what I have made available, however, any damage caused to your device will be your responsibility.

## Some useful informations

To get information about your device from Treble support, it is recommended to use the [Treble Info app](https://play.google.com/store/apps/details?id=tk.hack5.treblecheck&hl=pt_BR&gl=US).

I have provided some information about J4LTE from the [treble_experimentations repository](https://github.com/phhusson/treble_experimentations/wiki/Samsung-Galaxy-J4).

## System Support

Vendor 9.0 - 10.0 known work.

|Device Name|Codename|Support from OEM|Image Type|Architecture|
|:-:|:-:|:-:|:-:|:-:|
|[[Samsung Galaxy J4]]|j4lte|✓| A - A/B |arm_binder64 (a64) |

### Hardware support

| Component                 |      Comment                                              |
|---------------------------|-----------------------------------------------------------|
| Camera                    | Only custom with distortion                              |
| Speaker / Mic             | Works                                                    |
| Bluetooth                 | Works                                                    |
| WiFi                      | Works                                                    |
| SIM / Mobile Data / Voice | Calls work, but can't import or save contacts in SIM     |
| Offline Charging          | Doesn't work on some GSI.                                |
| Other feature             | MTP work on custom kernel                                |
---

Tested By: Drack112 - 2022

### Tools and Apk's

- Aida64 - Check device components
- AirFrozen - Freeze Magisk ( root ).
- com_termux_118 - Termux ( terminal emulator for android )
- Disable-Force-Encryption - Module to access the custom GSI and don't fall on BootLoop
- HavocOS - (My main GSI, currently with android 10. (Note: On my device, it is not possible to put a password on the lockscreen, it is in Loop with the Havoc logo))
- heimdall - ONLY FOR LINUX ( Tool to boot the TWRP Recovery, need and terminal to use )
- HorsePower.v2 - Kernel 
- Magisk.25.2 - Tool to make ROOT on device
- MagiskHideProps - Module to change the props of the device, only need it to pass in security net test
- Odin - ONLY FOR WINDOWS ( Tool to boot the TWRP Recovery on Windows (For linux, you can use JODIN))
- open_gapps-arm-10.0 - Minimal Google apps modules to use Play Store 
- SafetyNetFix - Module to pass in SafetyNet ( in the most cases he work )
- Shamiko - A better way to hide root
- Stock ROM of ***MY DEVICE*** - you can use some similar.
- twrp - Recovery for j4lte
- yasnac - SafetyNet Test Runner
