# Chimera
Unleash the full power of your Android device with Chimera, a powerful AIO module. This one-stop shop offers various customizable tweaks that push your processor and Android system to their limits, all while prioritizing speed and a smooth user experience. (Exclusive for MEDIATEK)

To use this module you must have one of the following:
- Installed Magisk or KernelSU
- BusyBox Latest (Brutal or Normal), or use busybox which is provided in the module

Important!
- Only For MEDIATEK Device
- Android 10 and above (SDK29+)

*Notes*:
- Add the application package name in  /InternalStorage/Chimera/applist_perf.txt for applications that are set to performance mode and run the app!

## Donations
- [Ko-Fi] (https://ko-fi.com/zy0x_noir)
- [Trakteer] (https://trakteer.id/zy0x/tip)

## About Module
### 1. Default Mode Options
This tweak modifies the device's persistent configuration to switch the default mode. Balance (with AI), High Performance, and Powersave. To achieve the perfect balance (powered by AI), you can fine-tune various settings within this module. These settings allow you to adjust CPU frequency or choose the optimal CPU governor for your needs.
#### More Balance Mode Options
This tweak functions to adjust the CPU frequency during Balance Mode, to balance battery and performance.
###### - Default
set the CPU frequency as the original setting.
###### - Downclock CPU Freq
reduces the CPU frequency (4, 5, 6, 7) to the 7th level from the highest.
###### - Disable 2 CPU Cores
disable CPU 3 and 6
###### - Powersave Governor CPU 4 - 7
change CPU governor 4 - 7 to "powersave"
### 2. Disable Thermal Engine
The script will look for several thermal configs and disable them completely in performance mode, and restore them again when in balance mode.
### 3. Deepsleep Enhancer
Set the sleep time speed of an Android, this affects how quickly the Android enters power saving mode for temperature stability and increased battery life. (affects notification delays)
### 4. Zram
Set the required zram size for an android. (available up to 6GB)
### 5. Swap
Managing swap requirements from internal memory, may be slower than ZRAM. (available up to 6GB)
### 6. GMS Doze
Functions to manage Google services, to improve performance and battery life. (affects delay notifications)
### 7. Dex2oat Optimizer
Compile dex files for each application to speed up opening or closing an application. (booting app)
### 8. Built-in BusyBox
BusyBox is integrated in magisk or kernelsu, for convenience and without additional busybox from outside. (optional)
### 9. Unity Big.Little Force
Serves to increase the efficiency of the CPU core for Unity applications.
### 10. Setting Renderer
Choose a renderer to use for the entire system such as OpenGL or Vulkan.
### 11. Window Animation Scale
Functions to reduce or turn off window animations. (like animation on open or close app)
### 12. Transition Animation Scale
Functions to reduce or turn off transition animations. (like transition app)
### 13. Animator Duration Scale
functions to reduce or turn off the duration of the animator. (like loading animation)
### 14. Internet Tweak
Increase internet speed and reduce latency by using improved scripts.
### 15. DNS Changer
Change the default DNS to custom DNS.
