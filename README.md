# Linux-Driver-USB-Bluetooth-5.0-ORICO-BTA-508
Linux Driver for USB Bluetooth 5.0 ORICO BTA-508 Adapter

```
cd ~/Downloads/ && wget https://mpow.s3-us-west-1.amazonaws.com/mpow_BH519A_driver+for+Linux.7z
sudo apt-get install -y p7zip-full && D=/lib/firmware;N=rtl8761;G=config;E=.bin
7z x ./mpow_BH519A_driver+for+Linux.7z;cd 202*/rtkbt-firmware/$D/rtlbt;S=sudo;D=$D/rtl_bt/$N
for C in a_ b_;do for L in fw $G;do F=$D$C$L$E;[ -f $F ]&&$S cp $F{,-`date +%s`};$S cp -f $N$C$L $F;done;done
cd ~/Downloads/ && rm -r 20201202_LINUX_BT_DRIVER/
```
