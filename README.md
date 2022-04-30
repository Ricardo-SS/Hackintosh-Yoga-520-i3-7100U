<h1 align="center"> EFI Lenovo Yoga 520-14IKB Intel-core i3 7100U </h1>
<h3 align="center"> Hackintosh EFI partition with support for macOS </h3>

<p align="center">
<img src="img/status.svg"/>
</p>

<p align="center">
<img src="img/foto.jpeg"/>
</p>

# Characteristics
- Screen: 14 inches with HD resolution (1366 x 768 pixels) and touch sensitive,
- Processor: Core i3 7100U,
- RAM memory: 4 GB,
- Graphics Card: Intel HD Graphics 620,
- Storage: HD 500 GB, SSD 128 GB
- Ports and Interfaces: USB 3.0, USB-C, HDMI, headphone jack, Bluetooth and Wi-Fi, memory card reader,
- Dimensions: 33 x 23.5 x 1.9 cm,
- Weight: 1.74 kilos

# It works
* Keyboard with lighting and shortcuts for brightness and volume.
* touchpad with gestures.
* wifi (has been replaced by an Intel 7265)
* usb 3.0 e USB type-C.
* battery indicator.
* intel UHD 620 graphics card with 2 gigas.
* webcam.
* card Reader.
* audio (see layout id files).
* HDMI connection (video and audio).
* brightness control keys f11 e f12. 
* volume control.
* touch screen.
* connect audio jack with microphone. 
* power control.
* sleep e auto sleep.

# Doesn't work

- Fingerprint reader.
- Native wifi (has been replaced by an Intel 7265)

# Updade MacOS Monterey 12.3.1

<p align="center">
<img src="img/Monterey.png">
</p>
<hr>
<h3>Update 30/04/2022</h3>

- Fixed video patch that didn't enable audio and video on HDMI
- the config.plist file has been replaced with the fix and the old one has been renamed to configOLD.plist if it is still useful in the future, but it can be removed from the folder without any problem in your hackintosh.

<h3>Update 19/04/2022</h3>

- Upadate ACPI DSDT, touchpad precision correction.
- Improved power management.
- Added kext yogaSMC.kext to activate secondary keys from F4 to F10 keys. <a link="https://github.com/zhen-zen/YogaSMC"> see installation instructions.</a>

<h3>Update 04/04/2022</h3>

- Added folder EFI OC version 0.8 Mod-no-acpi monterey 
- You can now boot windows through the opencore interface without problems, because oc acpi files are not injected into windows.
- All kexts updated until
- Fix quirks in config file
- Removed patch that showed 2 Gb of video memory as it was purely aesthetic.
- Added theme BsxImacGreen as standard

# Update MacOS Big Sur 11.6

<p align="center">
<img src="img/Big_Sur.png">
</p>

<h3>Update 04/04/2022</h3>

- Updated KEXTS Folder OC 0.7.8 Big Sur

# Screenshot 
<br>
<p align="center">
<img src="img/Tela.png"/>
</p>
<br>

# Bugs

- When turning on MacOS, sometimes the keyboard and mouse do not work on the OC screen until you enter windows and exit or reset nvram.
 <h4> * One way around this is by selecting the Mac partition and typing Ctrl + Enter to always start on it by default, and when using Windows, press the f12 or Fn + F12 key and choose the windows boot partition if it is on a disk different from mac. <br>
 * If the two systems tverem on the same disk a solution can be shut down using the power button or use an external mouse or keyboard, I can not describe this situation well since my systems are on different disks.  <br>
</h4><br>

# Heads up
* see id layout tests to enable headphone output microphone (jack connector)

# Bonus
- 2 Themas, 

<h3>how to install themes!</h3>

- Delete the Resources and Tools folders inside the EFI - OC folder and replace them with the ones inside the themes file.


# Credits

 - <a link="https://github.com/Ricardo-SS"> Ricardo-SS </a>
 - <a link="https://github.com/acidanthera"> Acidanthera </a>
 - <a link="https://github.com/dortania"> Dortania </a>
 - <a link="https://bitbucket.org/RehabMan/"> Rehabman </a>
 - <a link="https://www.olarila.com/profile/2-mald0n/"> MaLd0n </a>
 - <a link="https://github.com/OpenIntelWireless"> OpenIntelWireless </a>
 - <a link="https://github.com/zhen-zen"> zhen-zen </a>
 - <a link="#"> And others </a>
 