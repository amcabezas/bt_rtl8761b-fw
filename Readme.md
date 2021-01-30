#USB Bluetooth V5 on Gnu/Linux

Os:Pop!_OS
Kernel:5.8.0-7630-generic 
Device Info: Easy Idea 5V 

lsusb
```
ID 0bda:8771 Realtek Semiconductor Corp. Bluetooth Radio
```

Source Firmware:  
https://github.com/Realtek-OpenSource/android_hardware_realtek/tree/rtk1395/bt/rtkbt/Firmware/BT

```
git clone 

sudo -i cp rtl8761b_fw /usr/lib/firmware/rtl_bt/rtl8761b_fw.bin
sudo -i cp rtl8761b_config /usr/lib/firmware/rtl_bt/rtl8761b_config.bin 
```
