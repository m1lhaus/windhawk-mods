## 1.0.4 ([Oct 27, 2024](https://github.com/ramensoftware/windhawk-mods/blob/8195a025df8ce6bfbd9a3dab732811619d75d205/mods/taskbar-on-top.wh.cpp))

* Fixed the start menu opening on the left side of the screen, even if the icons on the taskbar are centered. The bug was caused by the attempt to change the incorrect jump list animation in version 1.0.3. As a result, if icons are centered, jump list animation will be incorrect again. This affects only Windows 11 23H2, there's no such issue on Windows 11 24H2.

## 1.0.3 ([Oct 19, 2024](https://github.com/ramensoftware/windhawk-mods/blob/ab4920afd69b029af1091d6f9598dd1c1c90eed8/mods/taskbar-on-top.wh.cpp))

* Improved compatibility with some programs which query the taskbar location, such as EarTrumpet.
* Adjusted jump list menu animations.

## 1.0.2 ([Oct 19, 2024](https://github.com/ramensoftware/windhawk-mods/blob/8d4c428d099ef834d8f616a0c78157a58b4ac458/mods/taskbar-on-top.wh.cpp))

* Fixed tray icon context menu not being clickable.
* Improved compatibility with some devices, mostly tablets and touchscreen devices.
* Fixed jump list position for multiple monitors in some cases.

## 1.0.1 ([Oct 5, 2024](https://github.com/ramensoftware/windhawk-mods/blob/2fb9f53e0e636376c07c33fa9a861345c4572e1a/mods/taskbar-on-top.wh.cpp))

* Improved jump list size and position handling.
* Adjusted the 1px taskbar border to be at the bottom of the taskbar.
* Fixed the start menu disappearing or being positioned incorrectly sometimes.

## 1.0 ([Oct 4, 2024](https://github.com/ramensoftware/windhawk-mods/blob/b43269d44eb047e3f27c015faca6fd365b0960d1/mods/taskbar-on-top.wh.cpp))

Initial release.
