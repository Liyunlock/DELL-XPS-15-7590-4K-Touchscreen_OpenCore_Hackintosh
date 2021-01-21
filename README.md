 ## XPS 15 7590 4K Touchscreen Opencore Hackintosh

 English/[中文](README_TW.md)

 **OpenCore Version** : [0.5.8](https://github.com/acidanthera/OpenCorePkg/releases)

**macOS Version** : macOS Big Sur 11.0 - macOS Big Sur 11.1(20C69)

~~macOS Version** : macOS Catalina 10.15.3(19D76) - macOS Catalina 10.15.5(19F101)~~

 ### Tested hardware configuration

 | Key                    | Value                                                        |
 | ---------------------- | ------------------------------------------------------------ |
 | CPU                    | 9th Generation Intel Core i7-9750h                           |
 | GPU                    | Intel Graphics UHD 630                                       |
 | Builtin Screen         | 15.6" 4K UHD (3840 x 2160) InfinityEdge touch IPS            |
 | RAM                    | SK Hynix HMA81GS6JJR8N 8G x 2                                |
 | SSD                    | KXG60ZNV1T02 NVMe TOSHIBA 1024GB                             |
 | Audio                  | Realtek ALC298                                               |
 | Wireless               | DELL DW1820A BCM94350ZAE or LENOVO DW1560 BCM94352Z (Replace)|
 ### User experience
 * Ultra power saving.
 * Almost no reduction in battery during sleep.
 * When using battery can keep its temperature low.
 
 ### Working

 * iGPU：working.
 * Wireless Card(**DW1560 or DW1820A**)：WiFi&BT working.
 * Touchscreen：working.
 * Audio：spkear & mic working.
 * Camera：working.
 * Input：keyboard & touchpad working.
 * HDMI Port：cold-plug working，hotplug half-working.
 * USB port：Type-A port x 2 (Max 5 Gbps) and Type-C port x 1 (Max 10 Gbps)
 * Brightness Controll：working.
 * Sleep/Wake：working.
 * SDCard Reader：not working.
 * Fingerprint：not working.

 ### Known Problem

. HDMI hot-plug 
   * Problem
     * After booting, the external screen is connected for the first time, and the output is displayed normally. After unplugging and reconnecting, the screen is completely black and only the mouse is displayed.
   * Workaround
     * Open the built-in screen cover for 1 second and then open, you will see the external screen display output normally.
 ### Waiting Test

 1. USB Type-C with external monitor

 ## Credit

 - Thanks 、[xxxzc](https://github.com/xxxzc/xps15-9570-macos)
