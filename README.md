# Dell-Optiplex-3020MT-OpenCore-EFI
Dell-Optiplex-3020MT-OpenCore-EFI, Hackintosh



https://github.com/tbwcjw/Dell-Optiplex-3020M-EFI   #####

This repository contains EFI files for my Dell Optiplex 3020M, tested and confirmed to work with macOS Catalina 10.15.7.


https://github.com/Kinetik/Dell-Optiplex-3020-sff-OC

This repository contains a fully working (with standard hardware) EFI package with you can use to install all macOS versions up to Big Sur.


https://github.com/varszegimarcell/Optiplex-3020-Hackintosh-OpenCore

This repository contains a guide on how to install macOS on the Dell Optiplex 3020, with the neccesary files.
iMac15,1


https://github.com/daliansky/Hackintosh

-------------------------------------------------------------------

## 我的硬件表：

cpu  :  E3-1225 V3

主板 ：  Dell optiplex 3020mt 主板    H81  

内存  ： DDR3 1333 2G*2

显卡 ：  核显HD P4600

声卡 ：  Realtek ALC280 

网卡 ：  RTL8111/RTL8168

SSD  ：  32G sata ssd

bios ：  AMI uEFI

-------------------------------------------------------------------

能正常引导安装 macOS Catalina 10.15.7

Dell optiplex 3020mt 主板 BOIS的选项很少， 

EHCI/XHCI Hand-off  ， CFG Lock  没有选项。

只能在 EFI-OC 中关闭。


-------------------------------------------------------------------

本项目在 https://github.com/tbwcjw/Dell-Optiplex-3020M-EFI  基础上，优化改动。感谢tbwcjw的无私分享。

增加了RTL8111网卡驱动，  

改动Realtek ALC280 声卡驱动








