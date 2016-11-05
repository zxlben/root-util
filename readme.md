#root util

##bootimg
modified boot.img for android debug
ro.debuggable=1
ro.secure=0
...

steps：
1.enter bootloader mode
2.fastboot oem unlock
3.fastboot falshing unlock
4.fastboot flash boot boot.img

##cfautoroot
root android device from cf auto root
url:http://cfautoroot.com/

steps:
1.enter bootloader mode
2.fastboot oem unlock
3.fastboot falshing unlock
4.fastboot boot autoroot.img

