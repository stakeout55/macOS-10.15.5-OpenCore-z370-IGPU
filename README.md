# macOS-10.15.5-OpenCore-z370-IGPU
This is my working EFI for Catalina 10.15.5 running Opencore. Hardware consists of: 
* Gigabyte z390 Gaming X
* 16GB GSkill DDR4 Ram
* NO GPU
* i5-9600k (iGPU with Intel UHD 630)
* 1x500gb NVME ssd
* 1x500gb 3D Sata ssd

Please note that 2 areas under my config.plist have been modified:

* PlatformInfo
  * Generic
  * PlatformNVRAM
  
Basic steps of the hack found here: https://dortania.github.io/OpenCore-Desktop-Guide/ 
  
These areas now hold default values that will work for boot and install but in order to get iServices working, you'll need to follow [this guide](https://dortania.github.io/OpenCore-Desktop-Guide/post-install/iservices.html)

Note: the serilas in the posted EFI are different from mine. Read the iServices guide if having issues signing into icloud and messages app!