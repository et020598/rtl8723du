# rtl8723du bluetooth driver

rtl8723du
===========
This repository includes drivers for the following card:

Realtek RTL8723DU

### Installation instruction
##### Requirements
For **Ubuntu**: You can install them with the following command
```bash
tar -zxvf rtl8723DU_BT_linux_20210324.tar.gz
cd rtl8723DU_BT_linux_20210324
sudo make install INTERFACE=usb
sudo insmod /lib/modules/$(unmae -r)/kernel/drivers/bluetooth/rtk_btusb.ko
reboot
