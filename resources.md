##USB Rubber Ducky downloads
The USB Rubber Ducky is a project with a lot of passion and innovation among the community. New members to the project are encouraged to get involved on the [USB Rubber Ducky Forums](https://forums.hak5.org/index.php?/forum/56-usb-rubber-ducky/). Here you can find payloads, web and desktop applications, new firmwares and help. Below is an incomplete listing of some featured USB Rubber Ducky projects to get you started.

##Payloads
One of the most valuable resources of the USB Rubber Ducky community project is sharing payloads. Featured payloads for various environments and applications can be found at the [USB Rubber Ducky Forums](http://forums.hak5.org/index.php?/forum/56-usb-rubber-ducky/).

Payloads are also hosted on the [USB Rubber Ducky Wiki](https://github.com/hak5darren/USB-Rubber-Ducky/wiki).


##Duckyscript
Duckyscript is the simple scripting language designed to make building a payload a breeze. With just a few simple commands you can turn any text file written in Notepad, Vi or TextEdit into an inject.bin ready to load on your USB Rubber Ducky and execute on your target PC.

[Ducky Script](https://github.com/hak5darren/USB-Rubber-Ducky/wiki/Duckyscript)

##Java Duckyscript Encoder
Duckyscript text file must be encoded into an inject.bin file and copied to the root of the Micro SD card in order for the USB Rubber Ducky to execute the payload.

The original cross-platform Java duckencoder.jar provides a means to encode duckyscript on Windows, Mac or Linux. [Download the Duck Encoder](https://github.com/hak5darren/USB-Rubber-Ducky/wiki/Downloads).

##Online Duckyscript Encoder
The [Duck Toolkit](http://ducktoolkit-411.rhcloud.com/Encoder.jsp) features an encoder supporting international keyboard layouts for convenient duckyscript compiling witout the need for a local version of the java duckencoder.

##DuckEncoder GUI
This cross-platform Java based duck encoder provides a graphical interface to script writing. Supporting multiple layouts and with an open source license this contribution comes from USB Rubber Ducky community member m1s73r. [Find Support and Download links here](https://forums.hak5.org/index.php?/topic/32943-encoder-duckyencoder-gui-10-editor-with-syntax-highlighting/).

##USB Rubber Ducky Toolkit
The [USB Rubber Ducky Toolkit](http://ducktoolkit-411.rhcloud.com/Home.jsp) website allows you to select and generate payloads for the USB Rubber Ducky with ease.


##Community Edition Encoder and Firmware
[Ducky-Decode](https://code.google.com/p/ducky-decode/) is a community edition and alternative to the stock USB Rubber Ducky Firmware and Encoder.

Firmware includes:

Support HID on Windows, Linux, Mac OS X, Android and iOS.
Support Mass Storage to emulate a generic USB Drive
Support Multiple Payloads in HID made triggered via Keyboard LEDs
Support Composite Device: Mass Storage and Keyboard
The Ducky-Decide Encoder supports multiple HID languages including:

US (United States)
GB (United Kingdom)
DE (German)
DK (Danish)
FR (French)
IT (Italian)
BE (Belgian)
NO (Norwegian)
PT (Portuguese)
SV (Swedish)
RU (Russian)
ES (Spanish)


##Simple-Ducky Payload Generator
The [Simple-Ducky Payload Generator](http://forums.hak5.org/index.php?/topic/28969-release-simple-ducky-payload-generator-v111-international-key-mappingkali-compatiblecustom-payload-builder/) allows you to quickly create reliable payloads. It supports all Debian Distros including Kali-Linux, Ubuntu, Mint, etc. The Installer will ensure all dependencies are met and with simple-ducky you can quickly create executables, inject.bin files, launch meterpreter or netcat listeners, generate custom password lists and much more.

Get the latest version of the [Simple-Ducky-Payload-Generator at Google Code](http://forums.hak5.org/index.php?/topic/28969-release-simple-ducky-payload-generator-v111-international-key-mappingkali-compatiblecustom-payload-builder/) and watch [Tutorial Videos](https://www.youtube.com/user/skysploit/videos) on installation and usage.


##VID and PID Swapper
All USB devices include a VID (Vendor ID) and PID (Product ID). The USB Rubber Ducky has the ability to swap its VID/PID to avoid antivirus software. [This Swapper Program](http://forums.hak5.org/index.php?/topic/29804-infoexecutablevid-pid-swapperexe-easily-swap-random-vidpid-numbers/) allows you to automatically change the vidpid.bin file on the USB Rubber Ducky.


##Flashing and Upgrading
Various firmwares exist for the USB Rubber Ducky to enable additional functionality, support additional languages or operating systems. Flashing the USB Rubber Ducky is a fairly simple process on Windows and Linux. [This guide](http://forums.hak5.org/index.php?/topic/28254-tutorial-re-flashingupgrading-the-ducky-winxp-32bit/) provides simple instructions.

Look here for [Unix/Linux/OSX instructions](https://github.com/hak5darren/USB-Rubber-Ducky/wiki/Flashing-ducky).


##Ducky Definitive Guide Document
[This document](https://docs.google.com/viewer?url=https%3A%2F%2Fducky-decode.googlecode.com%2Ffiles%2FThe%2520USB%2520Rubber%2520Ducky%2520Draft.doc) is advised reading for all newcomers to the project as it outlines connecting for the first time, generating your first ducky script, using the various encoders and firmware, sample ducky scripts and more.

##FAQ
[This Frequently Asked Questions](http://forums.hak5.org/index.php?/topic/28824-faq-frequently-asked-questions/) is maintained on the USB Rubber Ducky Forums.

##Quack Start Guide Video
[This 27 minute](https://www.youtube.com/watch?v=NeDYD9nb7PM) video covers the essentials of getting started with the USB Rubber Ducky.

##My First Payload
Learn how to write your first payload with this [simple tutorial](https://github.com/hak5darren/USB-Rubber-Ducky/wiki/My-first-payload).

##Source Code
The source is written in C and requires the AVR Studio 5 IDE from [atmel.com/avrstudio](http://atmel.com/avrstudio). Find the USB Rubber Ducky and Encoder firmware [Source Code on Github](https://github.com/hak5darren/USB-Rubber-Ducky).

##Ascii Ducks
```
      _      _      _      USB       _      _      _
   __(.)< __(.)> __(.)=   Rubber   >(.)__ <(.)__ =(.)__
   \___)  \___)  \___)    Ducky!    (___/  (___/  (___/ 
```